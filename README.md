# Buddhist Scripture Atlas

An interactive map of Buddhist scriptures and their transmission, with a dated timeline, reading links, and regional artwork carousels.

**Live map:** https://willavawang.github.io/buddhist-scripture-atlas/

## Run locally

This is a self-contained static site with no build step:

```sh
python3 -m http.server 8767
```

Open http://localhost:8767 in a browser.

## Publishing

GitHub Pages publishes the root of the `main` branch. Changes committed to `main` are deployed automatically. `.nojekyll` keeps the HTML served as a static file.

## Source

`index.html` contains the application, historical data, embedded artwork, and bundled map libraries. The map includes 19 places, 22 transmission routes, 61 reading or collection entries, and 54 artworks.

The map is a curated historical survey. Sources, reading links, and artwork credits are retained in the application. Third-party text, image, and library rights remain with their respective holders.

The move to GitHub Pages preserves the map's content and interface. The HTML is byte-for-byte identical to the previously published version.
