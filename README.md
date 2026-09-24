# The Rust Vaporizer Website

A mobile-first, one-page website for The Rust Vaporizer, a licensed
and insured laser surface restoration service serving Cincinnati and nearby
communities.

## Local Preview

Open `index.html` directly or run any static file server from the repository
root. The site has no build step or runtime dependencies.

## Netlify

Import this GitHub repository into Netlify with these settings:

- Production branch: `main`
- Base directory: leave blank
- Build command: leave blank
- Publish directory: `.`

The included `netlify.toml` applies the publish directory, security headers,
and sensible cache settings automatically.

## Adding Client Media

Project photos live in `assets/` and appear in the Results section of
`index.html`. To add another before and after pair, copy the
`<article class="before-after">` block, point it at the new images, and keep
the files around 1200px on the long edge. Use descriptive alternative text for
every project image.
