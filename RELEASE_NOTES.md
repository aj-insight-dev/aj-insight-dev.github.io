# GitHub Pages RC V1 — Release Notes

## What changed

- Wrapped the approved Squarespace V15.1 single-code-block portfolio in a standards-based standalone HTML document.
- Added recruiter-friendly page title and metadata.
- Added a minimal page-shell reset so the site does not inherit browser body margins outside Squarespace.
- Added `.nojekyll` for direct static serving on GitHub Pages.
- Added a defensive `.gitignore` for secrets, local files, build output, and private workspaces.
- Preserved the portfolio's own WAA V44 / Squarespace V15.1 source marker and presentation behavior.

## Intentionally unchanged

- SOLVE / IMAGINE / ALL architecture.
- Exhibit content and interaction logic.
- Existing Squarespace CDN image/video/audio URLs.
- Existing public resume/demo links.

## Phase 2 before leaving Squarespace

Migrate approved media assets away from Squarespace, update references, then regression-test the GitHub-hosted copy before canceling or changing the Squarespace site.

## RC V2.1 — Media consistency correction

- Keeps all portfolio video sources on the same Squarespace HLS delivery pattern.
- Removes the proposed one-off local StreamScout MP4 approach.
- Preserves the email "Copy email" fix.
- StreamScout's failing HLS source should be diagnosed/repaired at the source rather than by introducing a unique hosting path.
