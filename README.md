# Timezone Check

A tiny, dependency-free page that shows the current time in a chosen city and the hour offset from your own timezone and from Los Angeles.

## Features

- Text input with a datalist of common cities mapped to IANA time zone names
- Live local time in the chosen zone, updated every second with `Intl.DateTimeFormat`
- Hour offset versus the visitor’s timezone and versus `America/Los_Angeles`
- A short list of default cities that stays on the page
- Mobile-friendly layout, with light and dark colors from `prefers-color-scheme`
- No libraries and no network requests

## Usage

Open `index.html` in a browser, or enable GitHub Pages for this repository (serve the root) and open the published site.

## License

MIT. See [LICENSE](LICENSE). Copyright 2026 meinchord7.
