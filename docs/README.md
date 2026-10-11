# Documentation index

**Status: planning.** This index defines the documentation work to agree collaboratively. The documents listed below have not yet been written.

## Planned documentation

| Document | Purpose |
| --- | --- |
| Design specification | Problem, goals, non-goals, users, scope, requirements and acceptance criteria |
| Threat model | Assets, trust boundaries, threats, mitigations and residual risks |
| Architecture and data flows | Components, permissions, local baseline and separately assessed external communications |
| Privacy and data inventory | Data accessed, stored or transmitted; retention, deletion and user controls |
| Checkout behaviour | Detection, coupon attempts, comparison, throttling, cancellation and restoration |
| Testing strategy | Controlled checkout fixtures, compatibility, regression, network and permissions audits |
| Decision records | Agreed choices, alternatives and rationale |
| MVP roadmap | Milestones and release acceptance criteria |

## Recorded repository decisions

- Working project name: **LiteShopper**.
- Repository: **c-j-shaw/liteshopper**.
- Visibility: **public**.
- Licence: **MIT**.
- Default branch: **main**.
- Initial bootstrap on main; subsequent changes through short-lived branches and pull requests.
- Agree design and supporting documentation before implementing the extension.

## Open design questions

- Initial browser support and manifest compatibility.
- JavaScript or TypeScript, tooling and dependency policy.
- Bundled coupon data or user imports for the MVP.
- Supported checkout scope and merchant adapter strategy.
- Whether an optional remote update channel is justified.
- Safe comparison of totals and treatment of existing promotions.
- Permission lifecycle, data retention and failure recovery.

## Next collaborative step

Agree the problem statement and MVP boundaries, then develop verifiable requirements. Proposed options from the handoff are discussion inputs, not approved architecture.
