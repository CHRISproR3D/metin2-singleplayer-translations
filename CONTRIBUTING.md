# Contributing

Thank you for translating Metin2 Singleplayer! The full guide is in
[README.md](README.md) ([Polski](README_PL.md), [Türkçe](README_TR.md)).

In short:

1. Edit the `translation` column only - in the browser (the pencil, then
   **Propose changes**) or in a spreadsheet saved as CSV UTF-8 with commas
   (**Add file > Upload files**).
2. Never change `id` or `english`, and keep every variable and code of the
   English (`%s` `%d` `{0}` `[ENTER]` `|c...|r` `|H...|h` `|E...|e`).
3. Use only the letters of your language's code page (see the README); the
   bots' chat lines use plain a-z.
4. A new language: copy `template/` to a folder named with its ISO 639-1 code.
5. One pull request per language is easiest to review. Say in a sentence what
   you translated or corrected.

Every pull request is checked by `tools/validate.py`; a red check names the
file, the line and the reason - fix it and push again to the same branch.
`template/`, `tools/` and `.github/` are maintained by the project.

By opening a pull request you agree that your translation is used in Metin2
Singleplayer and shared under the same terms as the project
([CC BY-NC-ND 4.0](LICENSE)).
