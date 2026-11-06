# Anna Brigadere: *Sprīdītis* (1904)

*Latviski:* Annas Brigaderes pasaka lugā „Sprīdītis“ septiņās ainās, pirmais izdevums,
diplomātiska transkripcija vecajā rakstībā. Pirmā un otrā korektūra ir pabeigtas:
visi 11 279 vārdi un visas 1906 rindas ir salīdzinātas ar skenējumu.

The fairy-tale play *Sprīdītis* in seven tableaux by Anna Brigadere (1861–1933), first edition.
Sprīdītis, a boy too small for the work of the farm, leaves home to find the happy land, and
comes back.

| | |
|---|---|
| Title page | `Sprihditis. / Paꞩaka ꞩeptiꞥôs tehlojumôs. / Pehz muhꞩu tautas paꞩaku motiweem / no / Annas Brigader.` ("A fairy tale in seven tableaux, after the motifs of our folk tales") |
| Published | Rīga 1904. Censor's permit Riga, 25 November 1904 (in Russian, on the back of the title page). |
| Printed | `Drukats G. Ꞩchönfeldta grahmatu un noꞩchu drukatawâ Rigâ` — G. Schönfeldt's book and music printing house, Riga. |
| Contents | Seven tableaux (`Pirmais tehlojums` … `Ꞩeptitais tehlojums`), each with its list of characters (`Perꞩonas`, pp. 3, 19, 29, 41, 57, 71, 85) and its scenes (`Pirmais ꞩkats` …); songs within the scenes. Text pp. 3–96. |
| Language | Latvian, old orthography, Fraktur. |
| Source | National Library of Latvia: <https://gramatas.lndb.lv/periodika2-viewer/?lang=en#panel:pp\|issue:696766\|page:1>. The images used are those of the library's PDF of the book. |

## State

**Second proofreading complete** (6 November 2026): all 1,906 printed lines compared with their
image on the scan, for punctuation, hyphens, line breaks and indents. Most of the corrections of
this pass were brackets: the OCR lost many of the brackets around stage directions, or read the
opening one as `ꞩ`; every bracket was checked at the image, and every one now closes. Speaker
names of more than one word were marked as a whole.

**First proofreading complete** (2 November 2026): every word compared with its image on the
scan and confirmed or corrected; every stroke and accent decided at the image.

The cover (`transcription/cover.txt`), the title page (p. 1) and the censor's permit and
printer's imprint on its back (p. 2) were read at the image (6 November 2026).

## PDFs and plain text

Typeset versions are attached to the release
[`spriditis-2-lesung`](https://github.com/just-a-book-archivist/latvian-fraktur-books/releases/tag/spriditis-2-lesung)
(6 November 2026). A reading version (the play set anew: each speech a paragraph, the speaker's
name letter-spaced and the stage directions in smaller type, as in the print; each tableau on a
new page after its list of characters; a table of contents) and a diplomatic version (the cover,
the title page, the censor's permit and imprint, and every printed page line by line), each in
roman type and in Fraktur, as PDF/A, and both as plain text. In the Fraktur PDFs the stroked
letters are drawn over their base letter, so their text layer holds the base letter (`ſ` for
`ꞩ`).

The repository as it stood at this release is archived on Zenodo, citable as
[doi:10.5281/zenodo.24010956](https://doi.org/10.5281/zenodo.24010956).

## Notes on the print

- Where the print itself leaves a bracket or a quotation mark open, it is closed in the
  transcription and the place is noted (pp. 82, 88, 92, 93, 95). These are the only additions;
  they are listed in `transcription/anmerkungen.tsv` as `berichtigt` (corrected).
- On p. 79 the last `e` of `Prinzeꞩe` is set upside down; written as `e`.
- The title on the title page and on the cover is set with an `S` that shows no stroke
  (`Sprihditis`), while the text always has `Ꞩprihditis`. It is written as seen.
- The print is uneven in places (p. 81 most of all): indents and line breaks follow the page,
  not a rule.

## Layout of the files

The general rules are in [`../EDITORIAL_GUIDELINES.md`](../EDITORIAL_GUIDELINES.md). This is the
first play in the repository; in this book:

- **Speeches** begin with four spaces, after a blank line (not at the top of a page). The
  **speaker's name** is letter-spaced in the print and is written between underscores:
  `_Ꞩprihditis_.`, `_Wezà mahte_.`, `_1. galma kgs_.`; punctuation after the name stays outside.
- **Stage directions** stay in their brackets, as printed, also over several lines and across a
  page break. The smaller type of the print is not marked.
- **Two speakers joined by a brace** in the print (pp. 60, 63, 75): each name on its line, the
  common stage direction after the name at whose height it is printed; the brace is noted in
  `anmerkungen.tsv`.
- **Tableau and scene heads** (`Pirmais tehlojums.`, `Pirmais ꞩkats.`) without indent, with a
  blank line before and after; the characters of the scene below them, without underscores.
  The description of the place after a tableau head is a paragraph of four spaces.
- **Lists of characters** (`Perꞩonas.`) line by line, without indent and without underscores.
- **Songs:** one line of verse per line, eight spaces indent, twelve where the print indents
  further; a blank line before and after. `:,:` at the end of a line of a song is the sign for
  repeating it when sung, as printed.
- **Cover:** `transcription/cover.txt`, the printed title on the cloth binding; its picture is
  noted under `cover` in `anmerkungen.tsv`.

## The scans

`pages.tsv` links the image of every printed page in the library's viewer: page *p* is image
*p* + 4, e.g. p. 3 = `IMG00007`. The transcription was made from the images in the library's PDF
of the same copy, which are larger (1871 × 2496 px) than those of the viewer.
