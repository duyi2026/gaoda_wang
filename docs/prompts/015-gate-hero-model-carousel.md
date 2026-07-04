# Gate Handoff: Hero Model Carousel

Gate review scope:

- Review the owner handoff in `docs/prompts/013-owner-hero-model-carousel.md`.
- Review the tester handoff in `docs/prompts/014-tester-hero-model-carousel-review.md`.
- Review tester evidence in `docs/reviews/009-hero-model-carousel-review.md`.
- Decide whether a correction handoff is required.

Gate criteria:

- Hero visual uses model-array images from local assets.
- One random image is selected per model pool on page load.
- Carousel rotates every 3 seconds.
- Manual previous and next controls exist and do not trigger gallery navigation.
- Clicking the current image opens `gallery.html#...` for the displayed model.
- No release permission is granted unless explicitly approved separately.
