# Aarti - A little closer to the divine

A mobile-friendly collection of traditional Hindu aartis, with Hindi lyrics and English transliteration.

## Features

- 11 aartis with paired Hindi and English-script verses
- Search by deity, title, or lyrics
- Deity filters and alphabetical sorting
- Saved prayers stored in the current browser
- Adjustable reading text and keyboard-accessible lyrics dialog
- Responsive devotional design

## Run locally

No build step or package installation is required. Serve the `dist` directory with any static web server. For example, with Python installed:

```sh
python -m http.server 4173 --directory dist
```

Open http://localhost:4173 in your browser. Use a web server rather than opening the HTML file directly, because the app loads its lyrics from JSON.

## Source files

- `dist/index.html`: application layout
- `dist/style.css`: responsive styles
- `dist/app.js`: search, filters, saved prayers, and reading controls
- `dist/lyrics.json`: paired lyrics and reference links
- `.openai/hosting.json`: existing Sites deployment configuration

The app uses Google Fonts, Lucide icons from a CDN, and an externally hosted devotional photograph. These assets require internet access.

## Content references

Traditional lyrics are linked individually to their references on [Drik Panchang](https://www.drikpanchang.com/lyrics/aarti/aarti-collection.html). Regional wording and repetitions may differ. English displays transliteration, not a translation of meaning. This initial collection is not exhaustive.

The devotional photograph is credited to [Cenneys](https://www.hotelcenneys.com/blog/exploring-temples-in-salem.html). Third-party content and assets retain their respective rights; this repository does not grant a license to them.
