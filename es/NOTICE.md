# Spanish word list (ES)

**File:** `wordcrumble_words_ES.txt`

**Source:** Spanish spelling dictionary of the RLA-ES project (Hunspell `es` dictionary, version 2.8,
files `index.aff` / `index.dic` as distributed via https://github.com/wooorm/dictionaries),
initial developer: Santiago Bosio, https://github.com/sbosio/rla-es — original readme in
`ORIGINAL-README-RLA-ES.txt`.

**License:** the original is available under GPL 3+, LGPL 3+ or MPL 1.1+; this modified list is
distributed under the **Mozilla Public License 1.1** — full text in `MPL-1.1.txt`.

## Description of modifications (MPL 1.1, section 3.3)
Modified by ConceptCraft, 2026-10-12:
- All word forms were generated from the dictionary stems with their affix rules (suffixes,
  prefixes, cross products and one level of continuation classes); the result is a flat list.
- Stems starting with a capital (proper names, abbreviations) were left out.
- Only words of 2 to 9 letters; accents removed (á → a, ü → u) except ñ, which is kept.
- Removed: words without a vowel; 2-letter words that are not Spanish words on their own; a list of
  abbreviations (e.g. dto, izq, sra, pta, etc, dpto, impr, incl, inst, coord, univ).

## Correct spelling file
**File:** `wordcrumble_display_ES.txt` (added 2026-10-13), made by ConceptCraft from the same source.
One line per word of the list whose correct spelling differs from the game spelling: `game word<TAB>correct spelling`, for accents (arbol → árbol, si → si / sí). When more than one spelling exists, all are given, separated by " / ". Used for the printable word lists (PDF) in the game. Same license as the word list above.

This modified list will stay available here for at least 12 months.
