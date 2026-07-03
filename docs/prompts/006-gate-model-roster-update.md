# Gate Handoff: Model Roster Update

## Role

You are the gate reviewer for this model roster update. Decide only whether one later narrow handoff is allowed and whether release remains blocked. Do not modify `index.html`, assets, tester reports, product content, design, implementation, or prompts.

## Allowed Artifact

- `docs/reviews/004-gate-model-roster-update.md`

## Inputs

- Product artifact: `index.html`
- Owner handoff: `docs/prompts/004-owner-model-roster-update.md`
- Tester handoff: `docs/prompts/005-tester-model-roster-update-review.md`
- Tester report: `docs/reviews/003-model-roster-update-review.md`

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
