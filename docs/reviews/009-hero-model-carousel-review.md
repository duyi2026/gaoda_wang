# Hero Model Carousel Review

Overall result: `pass-with-notes`

Tester pass is evidence only and is not release permission.

## Evidence Checked

- Read `AGENT.md` and `docs/prompts/014-tester-hero-model-carousel-review.md`; review stayed within static hero carousel scope.
- Confirmed the hero visual in `index.html` now uses `assets/models/` images instead of `assets/future-hangar-silhouette.svg`.
- Confirmed the hero carousel defines 8 model pools:
  - `sazabi`
  - `nu`
  - `zeta`
  - `zz`
  - `unicorn`
  - `strike-freedom`
  - `rx-78-2`
  - `destiny`
- Confirmed the carousel pool references every local image in those 8 model folders:
  - `sazabi`: 4 of 4 images.
  - `nu`: 10 of 10 images.
  - `zeta`: 4 of 4 images.
  - `zz`: 4 of 4 images.
  - `unicorn`: 4 of 4 images.
  - `strike-freedom`: 8 of 8 images.
  - `rx-78-2`: 4 of 4 images.
  - `destiny`: 5 of 5 images.
- Confirmed page-load slide selection chooses one random image per model pool.
- Confirmed automatic rotation uses a `3000` millisecond interval.
- Confirmed previous and next controls exist, call `event.preventDefault()`, and are outside the image link.
- Confirmed the current image link is updated to `gallery.html#${slide.hash}` for the displayed model.
- Confirmed all referenced assets are project-local relative paths.
- Missing referenced files: 0.

## Issues Found

- No blocking issues found in the required review scope.

## Notes

- Browser verification in the in-app browser could not be completed because the browser security policy blocked reloading the current `file://` page. No browser-rendered result is claimed in this report.
- This report does not grant release permission; release remains subject to the downstream gate process.
