<img src="docs/brand/doumi-symbol.svg" width="56" height="56" alt="Doumi symbol">

# Doumi

**English** · [한국어](README.ko.md)

Doumi is an AI web vulnerability testing agent, a security agent powered by AI services that tests running web services and APIs for vulnerabilities. The agent, installed on your PC or an in-house server, tests only approved targets, AI suggests a verdict for each finding, and your team decides. Built by [Hanvietech](https://hanvietech.com/en/).

> **In development.** This repository holds public documentation: a product overview. The product source code is not public. Features and structure described here may change.

## How it works

1. **Target verification**: First confirms that the web service belongs to your company. Nothing is tested before that.
2. **Scoped testing**: The agent tests web services and APIs only within the set scope, rate, and time limits.
3. **AI + human verdict**: AI suggests whether each finding is real, a false positive, or needs review, with its evidence, and a reviewer decides.
4. **Fix & re-verify**: Re-tests only the fixed issue to confirm it is resolved. Unresolved issues stay tracked in the next test.

## Highlights

- **Approved targets, within set limits**: Tests only web services whose ownership is verified, and the agent itself enforces scope, rate, and time limits. Production environments are only observed, with no attack requests.
- **Shows how far each test reached**: If a login failed or a test was interrupted, the result shows "insufficient coverage" instead of "no vulnerabilities."
- **One finding per issue, people decide**: Merges results from multiple checks into one finding per issue and tracks new, recurring, and resolved issues. AI verdicts are suggestions; reviewers decide.
- **On a PC or an in-house server**: Install it on a developer PC and schedule tests for off-hours, or run it on an in-house server to test internal services. Login credentials never leave the agent.

## Early access

To receive a pre-release demo and details, choose Jikimi · Doumi early access in the [contact form on hanvietech.com](https://hanvietech.com/en/#contact), or email [ceo@hanvietech.com](mailto:ceo@hanvietech.com).

Sister product: [Jikimi](https://github.com/hanvietech/jikimi-docs) — AI code security agent

---

© 2026 Hanvietech. All rights reserved.
