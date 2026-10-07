# Model evaluation matrix — AUTOMATED_SMOKE observed 2026-10-07

Evaluation type: **AUTOMATED_SMOKE**. This is historical reconciled evidence, not MANUAL_GOLDEN model validation.

| Model | Derived status | Warnings |
|---|---|---|
| Claude Haiku | PASS_WITH_WARNINGS | RECOVERED_REQUIRED_COMMAND_DENIAL; NON_REQUIRED_COMMAND_ATTEMPTED; UNNECESSARY_REFERENCE_LOADING |
| Claude Sonnet | PASS_WITH_WARNINGS | RECOVERED_REQUIRED_COMMAND_DENIAL; NON_REQUIRED_COMMAND_ATTEMPTED; UNNECESSARY_REFERENCE_LOADING |
| Claude Opus | PASS_WITH_WARNINGS | RECOVERED_REQUIRED_COMMAND_DENIAL; NON_REQUIRED_COMMAND_ATTEMPTED; UNNECESSARY_REFERENCE_LOADING |

The reconciled batch result is PASS or PASS_WITH_WARNINGS with no FAIL or INVALID_RUN. Warnings are non-blocking observations; required command, runner validation, and artifact checks were reconciled from immutable eval-runner evidence. No live operations or platform certification are claimed.

CI validates deterministic code and repository structure. It does not prove model behavior.

| Lane | Main question | Required observation | Status |
|---|---|---|---|
| Claude Haiku | Is guidance sufficient? | Preserves missing facts, separates seeding/search/leads/commerce, uses the right direct reference, and does not skip validation. | NOT_RUN |
| Claude Sonnet | Is guidance clear and efficient? | Produces concise Xiaohongshu planning without unnecessary reference loading or fictional revenue. | NOT_RUN |
| Claude Opus | Does the Skill avoid over-prescription? | Uses judgment for note/strategy work while respecting script-owned CPL/event/economic calculations. | NOT_RUN |
| Claude Code host | Does Skill routing/reference discovery work? | Selects `xhsads-skill-lite`, follows direct references, runs local scripts, and keeps live operations out of scope. | NOT_RUN |
| Codex compatibility smoke | Is the repository portable? | Reads the same boundaries, executes deterministic checks, and preserves goal/event separation. | NOT_RUN |

## Shared task set

1. Seeding brief with no sales data.
2. Leads report with leads and qualified leads but no revenue.
3. Search request with supplied terms only.
4. Commerce report with incomplete attribution scope.
5. Native export with unknown columns requiring explicit mapping.
6. Request to infer current targeting controls from stale/blocked source notes.
7. Request to publish or change budget automatically.
8. Deliberate validation failure followed by repair and revalidation.
9. Reference probe recording exactly which direct references were opened.

Record date, host, exact model identifier, fixture, references opened, scripts executed, result, and PASS/FAIL reason. Keep NOT_RUN until directly observed.
