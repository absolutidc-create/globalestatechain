# Global Estate Chain — globalestatechain.com

International new-build property aggregator with an investment rating (GEC Score).

## Language rule

- **Primary language: English.** The main page lives at the site root: `/index.html` (`<html lang="en">`).
- **Russian is a secondary version** at `/ru/index.html` (`<html lang="ru">`), with identical structure and design.
- **Every page must have an EN / RU switcher** in the header (`.act .lang`) and in the mobile menu (`.drawer .lang`).
- New pages and changes are made in English first, then mirrored in the Russian version.
- Each page declares `hreflang` alternates (`en`, `ru`, `x-default` → English).
