# pannellum-translation
A central place for translated user-facing strings for the panorama viewer library called [Pannellum](https://github.com/mpetroff/pannellum).

[Pannellum](https://github.com/mpetroff/pannellum) includes english strings by default which can be overwritten to create a localized experience for the user/s.

The actual file names holding the strings should conform to the **[IETF language tags]([https://en.wikipedia.org/wiki/IETF_language_tag](https://www.venea.net/web/culture_code))** like so: `de.json` => `German`, sometimes you need more precision for some dialects e.g. German Swiss would be `de-CH.json`.
(Note: Previously **[ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1) and (if necessary) [3166-2](https://en.wikipedia.org/wiki/ISO_3166-2) Codes** were used for naming the translation files, but for translation languages `IETF language tags` are better suited).

If you have a request for a translation, **only** open an issue **if it doesnt exist already!** Instead express your interest inside the existing issue.

## NPM

You can find the package [here](https://www.npmjs.com/package/pannellum-translation).

## If you want to contribute:

Check out the american english [`en-US.json`](https://github.com/DanielBiegler/pannellum-translation/blob/master/en-US.json) file to get an idea of how this works.
Note how there are substitutions `%s` e.g. `"The file %s could not be accessed."`!

1. Fork this repo.
2. Create a branch e.g. `add-german-translation`.
3. Create a JSON file with the correct **IETF language tag** e.g. `es.json`.
4. Translate the strings.
5. Make a pull request.
6. Now your changes will be reviewed by native speakers to ensure quality.
7. If the quality is acceptable, your translation will be merged. Thank you for contributing.
