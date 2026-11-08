# Circularblocks portfolio

A lightweight static portfolio for CNC, manufacturing, construction, crafting and design. The geometric illustration is a concept study; completed project work is not yet presented.

## Local preview

From this directory, run `python -m http.server 8765 --bind 127.0.0.1`, then open `http://127.0.0.1:8765`.

## Structure

- `index.html`: content, navigation, accessible illustration and social-preview metadata.
- `style.css`: responsive layout, keyboard focus and reduced-motion support.
- `mark.svg`: original vector favicon and wordmark symbol.
- `.nojekyll`: serves the existing static files without Jekyll processing.

There are no runtime dependencies, analytics scripts or external fonts.

## Before merging website changes

Check desktop and narrow-screen layouts, keyboard navigation, local links and assets. Confirm project descriptions distinguish concepts from completed work. Keep private workshop notes, credentials and unpublished assets out of this public repository.

Changes on a review branch do not authorize a repository transfer or a Pages configuration change. Merging into the configured Pages source can deploy the updated website, so review publication intent before merging.
