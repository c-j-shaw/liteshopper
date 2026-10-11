# Contributing to LiteShopper

LiteShopper is in the design phase. Start with an issue or discussion of a proposed change before introducing implementation or dependencies.

## Workflow

1. Branch from the latest `main`, using a short name such as `docs/requirements`, `feat/coupon-results` or `fix/checkout-restoration`.
2. Keep changes focused and commits descriptive.
3. Open a pull request explaining the problem, the change and how it was checked.
4. Review privacy, security and documentation implications before merging.
5. Delete the branch after merging.

The initial repository bootstrap is committed directly to `main`. Subsequent work uses pull requests. Branch protection is not configured by this document.

## Review expectations

- Record proposed design decisions and their rationale; distinguish proposals from agreed decisions.
- Declare new permissions, network requests, dependencies and stored data.
- Keep implementation changes traceable to agreed requirements.
- Document meaningful verification and limitations. Runtime test commands will be established after tooling is selected.
- Use fictional data and controlled checkout fixtures. Do not commit credentials, personal shopping data, payment details or captured browsing histories.
- Keep dependencies minimal and review third-party licensing and provenance.

## Definition of done for documentation changes

The change is understandable, links resolve, requirements can be verified, and unresolved questions are clearly recorded. Do not describe planned privacy properties as audited guarantees.

For sensitive vulnerability reports, follow [SECURITY.md](SECURITY.md).
