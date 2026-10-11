# LiteShopper

Privacy-first, open-source browser extension for user-initiated coupon testing.

**Status: repository setup / pre-design.** No working extension is available yet. Requirements and architecture will be developed collaboratively before implementation.

## Project goals

Help users test coupon codes and identify the best result among the codes tested, while prioritising privacy, security, maintainability and transparent behaviour.

## Privacy and safety principles

- Coupon testing starts only when the user explicitly requests it.
- Prefer local processing and storage, with narrow, temporary permissions wherever practical.
- No behavioural analytics, profiling SDKs, tracking pixels or affiliate link/cookie rewriting.
- Do not transmit basket contents, account information or browsing histories.
- Any future external updates or community participation must be optional and documented. Downloads still expose network metadata, including an IP address.
- Never place an order or submit payment as part of coupon testing.
- Respect retailer restrictions and rate limits; do not bypass access controls.

These principles are design commitments, not claims about an implemented or audited product. Coupon application can alter existing promotions; safe cancellation and restoration will need explicit requirements.

## Planned sequence

1. Establish the repository and collaboration workflow.
2. Agree the design specification, threat model, data flows, privacy requirements and testing strategy.
3. Implement and validate a minimal prototype against a controlled mock checkout.
4. Consider additional merchant support after the baseline is verified.

Firefox-first support, Chromium compatibility, Manifest V3, language choices and coupon data sources remain tentative.

## Documentation

Start with the [documentation index](docs/README.md). It tracks planned documents and decisions still to be made.

## Contributing

Use short-lived branches and pull requests after this initial repository bootstrap. See [CONTRIBUTING.md](CONTRIBUTING.md) for the workflow and [SECURITY.md](SECURITY.md) for security reporting guidance.

## Licence

[MIT](LICENSE). Third-party coupon data and assets require their own provenance and licensing review.
