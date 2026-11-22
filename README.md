# Global Estate Chain — globalestatechain.com

International new-build property aggregator with an investment rating (GEC Score).

## Language rule

- **Primary language: English.** The main page lives at the site root: `/index.html` (`<html lang="en">`).
- **Other languages** mirror the English pages with identical structure and design: Russian `/ru/`, German `/de/`, French `/fr/`, Spanish `/es/`, Chinese `/zh/`, Arabic `/ar/` (`dir="rtl"`). Each folder also has `account/`.
- **Every page has a language dropdown** in the header (`.act .lang-dd`) and a full language list in the mobile menu (`.drawer .lang-list`), linking to the same page in each language.
- New pages and changes are made in English first, then mirrored in Russian and the other languages (de, fr, es, zh, ar are generated from the English source with translation dictionaries).
- Each page declares `hreflang` alternates for all languages plus `x-default` → English.
