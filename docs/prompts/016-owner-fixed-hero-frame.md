# Owner Handoff: Fixed Hero Frame

Scope: update the hero image carousel frame in `index.html` so the frame size does not change with different image dimensions.

Allowed artifact scope:

- `index.html`

Requirements:

- Keep the hero carousel frame at a stable fixed size per breakpoint.
- Show full images inside the frame without cropping.
- Use black fill/borders for unused space when image aspect ratio does not match the frame.
- Add an extra border line around the outside of the frame.
- Keep the existing carousel behavior, manual controls, and gallery link behavior intact.

Implementation note: this environment cannot spawn a real owner subagent unless the user explicitly requests subagents, so this handoff records the intended owner scope while the main thread performs the narrow static-file change.
