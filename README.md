# Amy Portfolio V16.2.2 — Demand Load

Final performance surgery on top of V16.2.1.

## Exactly two behavioral changes

### HLS
`hls.min.js` is no longer a top-level page dependency.

- Safari/native-HLS browsers use native playback without downloading hls.js.
- Other browsers dynamically request hls.js only when a video actually needs to be prepared.
- Existing HLS source, seeking, controls, timestamps and cleanup remain unchanged.

### Résumé preview
The small 300w front résumé thumbnail still loads normally.

The two 1500w preview pages:
- no longer have initial `src` attributes
- reserve their document aspect ratio with width/height attributes
- receive their real Squarespace `src` values the first time the résumé viewer opens
- remain cached/reused after that first open

The V16.2.1 fit-to-width résumé viewer is unchanged.

## Everything else
No layout, project, copy, metadata, accessibility, image-rendition, navigation or content changes from V16.2.1.

Shared core SHA-256:
`43b07d9aea99a183f18bb543df3798cfaa84309a8f6ccf26c78a621f2eea8215`

GitHub deployment:
- index.html
- .nojekyll

Squarespace:
- 01_SINGLE_CODE_BLOCK_SQUARESPACE_V16_2_2.html
