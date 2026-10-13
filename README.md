# WordCrumble word lists

The word lists used in the game **WordCrumble** by ConceptCraft (www.conceptcraft.nl),
in Dutch, English, German, French and Spanish.

Each list is a plain UTF-8 text file with one word per line, sorted, in lower case:
words of 2 to 9 letters, without proper names and abbreviations. They are made for a word game,
so they include all inflected forms (plurals, conjugations), like Scrabble or Wordfeud lists.

| Folder | Language | Words | Based on | License |
|---|---|---|---|---|
| `nl/` | Dutch | 100,556 | OpenTaal word list | CC BY 3.0 |
| `en/` | English | 105,241 | ENABLE | public domain |
| `de/` | German | 171,794 | DEMorphy German morphological dictionary | CC BY-SA 4.0 |
| `fr/` | French | 162,636 | Grammalecte lexicon v7.7 | MPL 2.0 |
| `es/` | Spanish | 223,791 | RLA-ES Hunspell dictionary | MPL 1.1 |

Every folder has a `NOTICE.md` with the exact source, the authors, the license and a description
of the changes, plus the license text where the license asks for it.

**Each list keeps the license of its source.** There is no single license for this repository.

## Special letters
The game uses letter tiles A–Z. Following Wordfeud:
- Dutch, English, French: accents are removed (café → cafe).
- Spanish: accents are removed, but ñ is kept.
- German: ä, ö and ü are kept, ß is written as ss.

## Correct spelling (display files)
For the printable word lists in the game, the folders `nl/`, `de/`, `fr/` and `es/` also contain
`wordcrumble_display_XX.txt`: per word of the list whose correct spelling differs from the game
spelling, a line `game word<TAB>correct spelling` (e.g. `arbol` → `árbol`, `strasse` → `Straße`,
`si` → `si / sí`). English needs no such file. Same license as the list in that folder.

## Contact
Questions or corrections: via www.conceptcraft.nl
