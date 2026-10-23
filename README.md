# Buddhist Scripture Atlas

An interactive map of Buddhist scriptures and their transmission, with a dated timeline, reading links, and regional artwork carousels.

**Live map:** https://willavawang.github.io/buddhist-scripture-atlas/

## Run locally

This is a static site with no build step:

```sh
python3 -m http.server 8767
```

Open http://localhost:8767 in a browser.

## Publishing

GitHub Pages publishes the root of the `main` branch. Changes committed to `main` are deployed automatically. `.nojekyll` keeps the HTML served as a static file.

## Source

`index.html` contains the application, historical data, artwork metadata, embedded map thumbnails, and bundled map libraries. Full artwork photographs are in `art/`. The map includes 19 places, 22 transmission routes, 61 reading or collection entries, and 74 artworks. Every location includes a seated Buddha sculpture in its gallery.

The Artwork checkbox starts unchecked. Enable it to see a representative image at every visible location, then select an image to open that gallery. Artwork dates are independent of the transmission timeline.

The map is a curated historical survey. Sources, reading links, and artwork credits are retained in the application. Third-party text, image, and library rights remain with their respective holders.

Artwork galleries remain chronological. Reproductions, damaged works, uncertain origins, source links, and photographic licenses are identified in the captions and expanded artwork details.
