# Changelog

The changelog lists changes to `pannellum-translation`.


### v1.4.0

#### Structural
- Use [IETF language tags](https://www.venea.net/web/culture_code) for the translation JSON filenames instead of [ISO 3166-1 alpha-2](https://en.wikipedia.org/wiki/ISO_3166-1) and [3166-2](https://en.wikipedia.org/wiki/ISO_3166-2) codes. (https://github.com/strarsis/pannellum-translation/pull/49)
- Use `prettifier` on all JSON translation files to ensure valid, consistent and well-formatted JSON translation files. (https://github.com/strarsis/pannellum-translation/pull/50; https://github.com/strarsis/pannellum-translation/pull/51; https://github.com/strarsis/pannellum-translation/pull/52)
- Project begins adding translation for strings for the newly introduced [UX interaction confirmation feature](https://github.com/mpetroff/pannellum/blob/71bac61e3b840061c8f3177230bc70282e0e8a02/src/js/pannellum.js#L143-L146) in Pannellum (e.g. in [de.json](https://github.com/strarsis/pannellum-translation/blob/master/de.json#L14-L17); [de-formal.json](https://github.com/strarsis/pannellum-translation/blob/master/de-formal.json#L14-L17)):
```js
twoTouchActivate: 'Use two fingers together to pan the panorama.',
twoTouchXActivate: 'Use two fingers together to pan the panorama horizontally.',
twoTouchYActivate: 'Use two fingers together to pan the panorama vertically.',
ctrlZoomActivate: 'Use %s + scroll to zoom the panorama.',  // One substitution: key name
````
(https://github.com/strarsis/pannellum-translation/pull/44)

#### Translations
- Add Chinese simplified translation (thanks [@charleserious](https://github.com/charleserious)). (https://github.com/strarsis/pannellum-translation/pull/45)
- Add Brazilian translation (thanks [@jhisse](https://github.com/jhisse)). (https://github.com/strarsis/pannellum-translation/pull/46)
- Add Czech translation (thanks [@oliverklimt](https://github.com/oliverklimt)). (https://github.com/strarsis/pannellum-translation/pull/47)
- Fix typo in German formal translation. (https://github.com/strarsis/pannellum-translation/pull/48)
