# Buddhist Scripture Atlas

A geographic map of Buddhist scriptures and their transmission, with a dated timeline, reading links, and regional artwork carousels.

Live site: https://buddhist-scripture-atlas.dewychime19.chatgpt.site

The live site currently requires the owner's ChatGPT sign-in.

## Run locally

This is a buildless static site. Serve the `dist` directory:

```sh
python3 -m http.server 8767 --directory dist
```

Open http://localhost:8767 in a browser.

## Source

- `dist/index.html` contains the application, historical data, embedded artwork, and bundled map libraries.
- `.openai/hosting.json` retains the existing Sites project and static hosting configuration.
- The current publication includes 19 places, 22 transmission routes, 61 reading or collection entries, and 54 artworks.

The map is a curated historical survey. Sources, reading links, and artwork credits are retained in the application. Third-party text, image, and library rights remain with their respective holders.

This repository preserves the published map without changing its content or interface. Its HTML is byte-for-byte identical to the Site source at commit `70c7c042939a3c89ffa208ece5e38d87373d55b9`.
