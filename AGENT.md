# Agent Harness Rule

Main Agent is coordinator only. Main Agent must not directly implement product content, design, UI, app code, prompts, LLM calls, scoring, reports, storage, analytics, testing reports, gate reports, or release decisions.

For every substantive artifact:

1. Main Agent writes a narrow handoff in `docs/prompts/`.
2. The owner subagent creates exactly the allowed artifact.
3. Main Agent performs only basic verification.
4. If verification fails, Main Agent returns the artifact to the owner subagent; Main Agent does not fix it directly.
5. Main Agent writes a tester handoff.
6. Tester subagent writes a report in `docs/reviews/`.
7. Tester pass is evidence only, not implementation or release permission.
8. Main Agent writes a downstream gate handoff.
9. Gate reviewer decides whether one later narrow handoff is allowed.
10. Release is blocked until an explicit release gate approval.

All unknown project facts must remain `to-be-confirmed`.

Full rule: `docs/runbooks/project-harness-rule.md`
