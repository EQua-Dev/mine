# Richard Uzor — Portfolio

Static single-page portfolio served via GitHub Pages at
https://equa-dev.github.io/mine/

## Structure

- `index.html` — the entire site (markup + styles, no build step)
- `assets/` — app logos
- `assets/shots/` — app screenshots (see the README in that folder)

## Before publishing

1. Add `Richard-Uzor-CV.pdf` to the repo root (both "Download CV" buttons link to it).
2. Add screenshots to `assets/shots/` and swap the placeholders in `index.html`.
3. Confirm the LinkedIn URL slug in the contact section is the live one.

## Editing

Everything is plain HTML and CSS in one file. Design tokens live in the
`:root` block at the top of the `<style>` tag.
