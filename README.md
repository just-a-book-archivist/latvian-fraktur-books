# Latvian books in Fraktur — diplomatic transcriptions

*Latviski:* šeit ir vecu latviešu grāmatu diplomātiskas transkripcijas — teksts tieši tāds, kāds
tas iespiests fraktūrā, vecajā rakstībā. Katra lappuse no jauna nolasīta ar teksta atpazīšanu, un
katrs vārds pārbaudīts pret skenējumu. Teksts netiek pielāgots mūsdienu rakstībai: `ſ`, `w`, `ꞩ`,
`ꞥ`, `ł` un garumzīmes ar `h` paliek, kā iespiestas. Pirmā korektūra ir pabeigta; pieturzīmes un
rindu pārnesumi vēl tiks pārbaudīti.

This repository holds transcriptions of Latvian books printed in Fraktur, in the orthography
before the reform of the 1920s. Each page was read anew with OCR from the scans and corrected by
hand against them. The text is **diplomatic**: it keeps the page as printed — line breaks, long
`ſ`, the stroked letters of the old orthography, accents — and is not normalised toward modern
Latvian.

## The books

| Folder | Book | State |
|---|---|---|
| [`1911-skalbe-latvju-dainu-izlase-iii`](1911-skalbe-latvju-dainu-izlase-iii/) | Kārlis Skalbe (ed.), *Latvju dainu izlase* III: *Dziesmas un jaunība*. Pēterburga: A. Gulbis, [1911]. Folk songs. | first proofreading complete |

Each folder has a `README.md` with the book's details, its source scans and what is still to be
done.

## How the texts are made

1. **Scans** from the Internet Archive (University of Toronto copies), in one case three pages
   from the National Library of Latvia's copy. `pages.tsv` in each book folder says which image
   is which printed page, so every line can be checked against the print.
2. **OCR** with Tesseract and the Fraktur model `frak2021`, with every dictionary switched off,
   so that nothing is "corrected" toward German or modern Latvian. The result is only a draft:
   the model does not know the stroked letters (`ꞩ ꞥ ł ꞧ ꞣ ꞡ`) and misreads most accents.
3. **First proofreading:** every word of a book is shown as a cut-out from the scan next to its
   transcription and confirmed or corrected by a person; each stroke and accent is decided at the
   image. Nothing in the text was corrected automatically.
4. **Still to come:** punctuation, line breaks and lost or doubled lines (which a word-by-word
   check does not see), a cross-check between the four Skalbe volumes, and typeset editions in
   the old orthography, in the standard of 1922 and in today's spelling.

What a transcription changes and keeps is set out in
[`EDITORIAL_GUIDELINES.md`](EDITORIAL_GUIDELINES.md).

## What is here

| | |
|---|---|
| `<book>/transcription/pNNN.txt` | **The text.** One file per printed page, lines as printed. Blank pages are empty files. |
| `<book>/transcription/anmerkungen.tsv` | Notes on single places: printer's signatures, ornaments, stamps, damaged type, doubtful letters and how they were decided. Written in German during the work; columns: page, kind (`satz` = typesetting, `scan` = the copy or image), place, note. |
| `<book>/pages.tsv` | Printed page → image of the source scan. |
| `lexicon/forms.tsv` | Every word form confirmed in the books, with volume and count. In the old orthography, as printed. |
| `EDITORIAL_GUIDELINES.md` | The rules of the transcription. |

The front matter (cover, series lists) and the publisher's advertisements at the end of some
volumes are not included yet; they were not part of the first proofreading.

## The characters

The old orthography marks palatal consonants with a stroke through the letter. Unicode has the
Latvian Fraktur forms, used here:

| here | modern | example (here → modern) |
|---|---|---|
| `ꞩ` `Ꞩ` | s, š (`ꞩch`) | `Dſeeꞩmas` → *Dziesmas* |
| `ꞥ` `Ꞥ` | ņ | `Daiꞥu` → *Daiņu* |
| `ł` | ļ | `ſała` → *zaļa* |
| `ꞧ` | ŗ, r | `Gaꞧam` → *Garam* |
| `ꞣ` | ķ | `riꞥꞣodama` → *riņķodama* |
| `ꞡ` `Ꞡ` | ģ | |
| `ſ` (long s, no stroke) | z, ž (`ſch`) | `ſała` → *zaļa* |

A font with these characters is needed to read the files, for example Noto Serif, DejaVu or
Junicode.

## Licence

The books are in the public domain (Kārlis Skalbe died in 1945). The transcriptions, notes,
guidelines and the lexicon are published under
[CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/), see `LICENSE`. How to cite:
`CITATION.cff`, or "Cite this repository" on GitHub.

## About this repository

It is exported from a working repository and grows by one commit per finished pass; each pass is
tagged and published as a release. It is an edition, not a software project. If you think a
place is wrong, give book, page, line and what the scan shows.
