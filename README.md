# josephklane.com

Personal site for Joseph K. Lane. Static HTML, no build step, no dependencies.

## Structure

```
index.html     single page — markup, CSS, and JSON-LD all inline
headshot.jpg   640x720, masthead photo
```

## Local preview

Open `index.html` in a browser. Paths are relative, so it renders correctly from
the filesystem without a server.

## Deploying

Hosted on Cloudflare Pages, connected to this repo.

- Build command: *(none)*
- Build output directory: `/`
- Pushes to `main` deploy automatically

## Things not to break

- **`<link rel="canonical">` in the head.** Cloudflare serves this site at both
  `josephklane.pages.dev` and `josephklane.com`. The canonical tag is what stops
  those being treated as duplicate pages.
- **The `Person` JSON-LD block.** The `sameAs` array should stay in sync with
  wherever profiles actually live; a dead link there is worse than no link.
- **Image dimensions.** The `width`/`height` attributes on the masthead `<img>`
  must match the real file, or the browser reserves the wrong space and the
  layout shifts as the image loads.

## Layout notes

The masthead intentionally spans wider (52rem) than the body copy (38rem). Body
text is held near a 75-character measure for readability; widening the text
column to match the header undoes that.
