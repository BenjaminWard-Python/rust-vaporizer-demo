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

The results section in `index.html` is intentionally marked `hidden` until
real client media arrives. Replace the placeholder markup with optimized
images and video, remove the `hidden` attribute, and restore the Results link
in the main navigation. Use descriptive alternative text for every project
image.
