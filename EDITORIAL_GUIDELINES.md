# Editorial guidelines

What `transcription/pNNN.txt` contains, and every way it departs from the print. The principle:
**the scan is the authority.** The Latvian stays in the old orthography of its print and is
smoothed neither toward German nor toward modern Latvian: `w` stays `w`, `ſch` stays `ſch`,
`mahſina` stays `mahſina`. Any departure from the page is listed here; one that is not is an
error.

These rules hold for all books in this repository. What differs from book to book (verse or
prose, titles, separators) is in each book's `README.md`.

## Letters

| Matter | Rule |
|---|---|
| Long `ſ` | kept as printed. Turning `ſ` into `s` is a task for a reading edition, not for the transcription. |
| Stroked `ſ` | written `ꞩ` / `Ꞩ` (U+A7A9 / U+A7A8), the character Unicode provides for Latvian Fraktur. The stroke marks the sound: `ſ` without stroke is voiced *z*, with stroke voiceless *s* (`Dſeeꞩmas` = modern *Dziesmas*); likewise `ſch` = *ž*, `ꞩch` = *š*. The print has the long form with a stroke, which has no character of its own; `ꞩ` stands for it. |
| Other stroked letters | `ꞥ` / `Ꞥ` (U+A7A5 / U+A7A4) for *ņ*, `ł` for *ļ*, `ꞧ` for *ŗ*, `ꞣ` / `Ꞣ` for *ķ*, `ꞡ` / `Ꞡ` (U+A7A1 / U+A7A0) for *ģ*. Each stroke was decided at the image; OCR does not see them. |
| Accents | circumflex `â ê î û` and grave `à è ì ù` kept as printed, and the diaeresis in `naïwi` (*Pazemīgas dvēseles*, p. 39). Each was decided at the image, also where the OCR showed none. |
| Double oblique hyphen `⸗` | written as a plain `-`: a feature of the Fraktur type, not of the text. |
| Antiqua | a few songs in *Latvju dainu izlase* III are set in roman type, in Latgalian spelling with macrons and hooks (`ū ī š á`, `ņ` with comma below, U+0146 — not the Fraktur `ꞥ`). Written as printed; the change of type is not marked in the text but noted in `anmerkungen.tsv`. |

## Lines and spaces

| Matter | Rule |
|---|---|
| Line breaks | as printed; one printed line, one line in the file. A hyphen at the end of a line stays. |
| Word spacing | always one space between two words. The wider gaps of justified lines are not kept. |
| Space before `! ? ; :` | not kept where the print sets one by Fraktur custom; the transcription writes them close. |
| Blank lines | mark what the print separates by space: stanzas, songs, paragraphs, titles. See each book's `README.md`. |

## Left out, and noted in `anmerkungen.tsv`

| Matter | Rule |
|---|---|
| Running heads | left out, title and page number alike. The page number is in the file name. |
| Printer's signatures | the signature at the foot of a sheet's first and third page (`1*`, `2`), and the short title beside it, left out and noted. |
| Ornaments, rules | left out and noted; the short rule under each poem in *Sapņi un teikas* is left out without a note. |
| Stamps, pencil | owners' and library stamps, shelf marks in pencil: not print, left out and noted. |

## Errors of the print

Damaged type and printer's errors stay in the text as printed and are noted in
`anmerkungen.tsv`. A misprint that makes no word may be corrected when the intended form is
beyond doubt; each such place would be listed below. So far there are none.

## Normalised

Nothing. No form has been changed toward another spelling.
