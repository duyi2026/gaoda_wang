# Gate Handoff: Image Gallery Integration

## Role

You are the gate reviewer for the image/gallery integration update. Decide only whether one later narrow handoff is allowed and whether release remains blocked. Do not modify `index.html`, assets, tester reports, product content, design, implementation, or prompts.

## Allowed Artifact

- `docs/reviews/006-gate-image-gallery-integration.md`

## Inputs

- Product artifact: `index.html`
- Project-local assets: `assets/`
- Owner handoff: `docs/prompts/007-owner-image-gallery-integration.md`
- Tester handoff: `docs/prompts/008-tester-image-gallery-integration-review.md`
- Tester report: `docs/reviews/005-image-gallery-integration-review.md`

## Gate Questions

Record:

- Whether the tester evidence is sufficient to allow one later narrow follow-up handoff, if needed.
- Whether any unresolved issue requires returning work to the owner.
- Whether release is approved or blocked.

## Required Gate Policy

- Tester pass is evidence only and is not release permission.
- Release must remain blocked unless there is explicit release gate approval.
- If release is blocked only because explicit release approval is absent, say that clearly.
- Unknown project facts must remain `to-be-confirmed`.

## Report Requirements

Write a concise Markdown report with:

- Gate result: `allow-next-handoff`, `return-to-owner`, or `release-approved`.
- Release status.
- Evidence reviewed.
- Any required next narrow handoff, if applicable.
