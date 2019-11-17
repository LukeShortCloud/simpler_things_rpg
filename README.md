# Simpler Things RPG Engine

An open source role-playing table-top game engine. PDF releases of the game rules and other supporting documents are available [here](https://github.com/ekultails/simpler_things_rpg/releases).

Goals:

* Simple rules
* Quick references
* Fast setup time for new campaigns and players
* Flexible enough to work with any genre

## Build Releaess

Each tagged release on GitHub has a related release that provides PDF files.

```sh
for guide in $(ls -1 *.md | cut -d\. -f1); do pandoc -f markdown -t latex -o ${guide}.pdf ${guide}.md; done
```

## Licenses

All documents are licensed under open source licenses.

* [GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html)
    * simpler_things.md
    * stre_gm_reference_sheet.md
* [WTFPL](http://www.wtfpl.net/about/)
    * stre_character_sheet.md
