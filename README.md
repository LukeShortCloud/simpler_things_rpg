# Simpler Things RPG

An open source tabletop role-playing game (TTRPG) engine. PDF releases of the game rules and other supporting documents are available as assets [here](https://github.com/ekultails/simpler_things_rpg/releases).

Most TTRPGs are complicated, require large and expensive reference guides, and take too long to learn all of the rules. Simpler Things RPG was created to make the focus on the characters, stories, and fun. Not learning the rules.

Goals:

* Simple rules
* Quick references
* Fast setup time for new campaigns and players
* Flexible enough to work with any genre (fantasy, space sci-fi, western, etc.)

## Extras

[Simpler Things Extras](https://github.com/ekultails/simpler_things_extras) provides complementary content such as character sheets and reference guides.

## Build Releases

Each tagged release on GitHub has a related release that provides PDF files.

```sh
for guide in $(ls -1 *.md | cut -d\. -f1); do pandoc -f markdown -t latex -o ${guide}.pdf ${guide}.md; done
```

## License

[GNU Free Documentation License](https://www.gnu.org/licenses/fdl-1.3.en.html).
