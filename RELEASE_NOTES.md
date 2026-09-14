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

## RC V2.2 — StreamScout source repair

- Replaced the stale StreamScout Squarespace HLS asset with:
  `db0a1a2a-1865-4fe1-9900-564ef1b90b4f`
- StreamScout remains on the same Squarespace HLS delivery pattern as the other portfolio videos.
- Updated StreamScout to the reviewed 91.3-second Demo 1 V2 reel.
- Reviewed chapter jumps:
  FIND 00:07 · VERIFY 00:20 · STATE 00:23 · EXPERIENCE 00:25 · PROTECT 00:42 · GOVERN 01:28.
- No other exhibit video source was changed.
