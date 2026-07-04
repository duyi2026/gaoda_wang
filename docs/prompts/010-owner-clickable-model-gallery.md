# Owner Handoff: Clickable Model Gallery

Scope: update the static Gundam showcase so the 8 model cards in `index.html` link to a corresponding image page, and add price buttons on every image in that image page.

Allowed artifact scope:

- `index.html`
- `gallery.html`

Requirements:

- Keep all image paths project-local and relative.
- Do not invent prices, inventory, official brand claims, or purchase promises.
- Preserve unknown commercial facts as `to-be-confirmed`.
- Each of the 8 model cards must be clickable.
- The image page must show all local images for the selected model folder.
- Every displayed gallery image must have a visible price button at the lower-right corner.

Implementation note: this environment cannot spawn a real owner subagent unless the user explicitly requests subagents, so this handoff records the intended owner scope while the main thread performs the narrow static-file change.
