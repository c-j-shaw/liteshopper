# Security policy

## Project status

LiteShopper has no released extension or supported runtime versions yet. Security requirements and verification procedures will be developed before implementation.

## Reporting security concerns

Do not put credentials, personal data, payment details or usable exploit details for an unpatched vulnerability in a public issue.

If GitHub offers **Report a vulnerability** under this repository's Security tab, use that private channel. Availability of private reporting has not yet been confirmed. If it is unavailable, open a minimal issue asking the maintainer to establish a private reporting channel, without sensitive details.

A dedicated reporting channel, supported-version policy and response expectations must be agreed before the first release.

For a private report, include affected code or version, reproduction steps using fictional data, expected and observed behaviour, and potential impact.

## Security design priorities

- Minimise permissions and access to sensitive checkout content.
- Prevent undeclared data transmission and affiliate attribution changes.
- Validate coupon data and assess update integrity if updates are introduced.
- Prevent unintended order submission and define cancellation and restoration behaviour.
- Assess interactions with untrusted retailer pages and third-party scripts.

These are priorities for the forthcoming threat model, not completed controls or audit results.
