# Anthony Joiner

A responsive editorial redesign of AnthonyJoiner.com, inspired by the oversized outline typography, image stage, and project navigation of belenjones.com. Content and photography adapted from Anthony's existing website, with original implementation.

## Run locally

No dependencies or build step. From this directory:

```sh
python3 -m http.server 4173
```

Open http://localhost:4173.

## Deploy

Serve this directory as a static site. A GitHub Pages workflow is included; select **GitHub Actions** as the Pages source in repository settings to enable it. The workflow deploys only the website files and assets.

The custom domain is intentionally not set in this repository. AnthonyJoiner.com currently serves a Kartra page through a domain frame; switching the domain requires configuring the hosting destination and DNS at the current domain provider.

## Editing

- `app.js`: chapter content, destinations, and interactions.
- `style.css`: responsive layout, typography, and animation.
- `index.html`: homepage, navigation, and accessible dialogs.
- `assets/`: optimized existing photography and locally hosted fonts.

Every chapter supports direct linking (`#blooksy`, `#publishing`, and so on). Navigation supports keyboard input, native dialog focus management, Escape to close, and reduced motion preferences. The site uses no tracking, form backend, or runtime dependencies.

## Sources

- Content and images: https://anthonyjoiner.com/ → https://blooksy.kartra.com/page/BwV300
- Layout reference: https://www.belenjones.com/
- Fonts: Archivo Black and Space Grotesk, via Google Fonts (SIL Open Font License).
