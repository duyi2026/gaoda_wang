# Owner Handoff: Hero Model Carousel

Scope: update the hero visual on `index.html` so it uses model-array images instead of the original hangar silhouette.

Allowed artifact scope:

- `index.html`

Requirements:

- Use images already present under `assets/models/`.
- Rotate automatically every 3 seconds.
- Provide manual previous and next controls.
- Clicking the current hero image opens `gallery.html` at the corresponding model hash.
- Keep paths project-local and relative.
- Do not invent prices, inventory, purchase promises, brand claims, or authorization facts.

Implementation note: this environment cannot spawn a real owner subagent unless the user explicitly requests subagents, so this handoff records the intended owner scope while the main thread performs the narrow static-file change.
