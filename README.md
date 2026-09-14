# Amy J. Watson-Markley — Portfolio

Recruiter-facing portfolio for **Senior Technical Business Analyst | Business Systems & Data Integration | AI-Enabled Solutions** work.

## Deployment

This repository is intended for GitHub Pages at:

`https://aj-insight-dev.github.io/`

GitHub Pages publishing source: **main branch / root**.

## Release lineage

- Presentation source: `Bayou_Portfolio_Squarespace_V15_1_Ear_Scroll_Fix.zip`
- Embedded portfolio source marker: `WAA-V44-Squarespace-v15-1`
- Packaging release: **GitHub Pages RC V1**
- The portfolio experience itself is intentionally unchanged. This release only converts the Squarespace single-code-block package into a standalone HTML document and adds GitHub Pages packaging.

## Public-release boundary

This repository is **presentation-only**. It must not contain private research archives, credentials, `.env` files, API keys, client-private data, or backend/project implementation source that is not intentionally public.

## Temporary external asset dependency

RC V1 intentionally preserves the live portfolio's existing Squarespace-hosted images, video, audio, and selected `grannydsolutions.com` links. **Do not cancel Squarespace yet.** A later asset-migration release can make the portfolio independently hosted after rights/provenance review and regression testing.

## Copyright

Copyright © Amy J. Watson-Markley. No open-source license is granted by this repository.

## RC V2.1 consistency correction

This release keeps **one media-delivery pattern** for the portfolio: existing Squarespace-hosted HLS media remains unchanged for every video, including StreamScout.

Only the email interaction changed: email buttons now copy the public address instead of invoking a registered webmail handler.

StreamScout media troubleshooting is intentionally separate from this release. Do not special-case one exhibit with a local MP4 while the rest of the portfolio still uses Squarespace HLS.

## RC V2.2 StreamScout repair

StreamScout uses the replacement Squarespace HLS asset while preserving the portfolio-wide media architecture. No local GitHub MP4 special case is used.
