# Klaimee

Klaimee is a Y Combinator (Spring/P26 batch) startup building certification, financial guarantee, and liability insurance for AI agents running in production. Klaimee evaluates an autonomous agent across risk dimensions — scope, data exfiltration, unauthorized action, output integrity, adversarial manipulation, behavioral stability, model drift, and operational control — then issues a letter-graded certification report with remediation guidance and a Klaimee-Verified badge that AI vendors use to clear enterprise procurement. Certified agents are backed by a financial guarantee and by AI liability insurance priced against the certification score, covering the gap that traditional E&O and cyber policies explicitly exclude.

- Website: https://www.klaimee.ai/
- Blog: https://www.klaimee.ai/blog
- Get started: https://www.klaimee.ai/apply
- Contact: contact@klaimee.ai
- Y Combinator: https://www.ycombinator.com/companies/klaimee

Founded 2026 by Ines Boutemadja (CEO) and Julien Catonnet (CTO). San Francisco.

Backed by: y-combinator

## API surface

As of the 2026-07-19 enrichment pass Klaimee publishes **no public API, SDK, developer
documentation, or OpenAPI**. The product is delivered as a human-run certification and
underwriting engagement, with an adversarial-testing playground onboarded through an
intake form rather than a programmatic endpoint. Spec-dependent artifacts (openapi/,
authentication/, scopes/, errors/, conventions/, skills/, mcp/, arazzo/) are therefore
intentionally absent rather than fabricated.

## Artifacts

| Artifact | File | Method |
|---|---|---|
| llms.txt | `llms/klaimee-llms.txt` | searched (verbatim from https://www.klaimee.ai/llms.txt) |
| Well-Known | `well-known/klaimee-well-known.yml` | searched (all `/.well-known/` paths 404; `/llms.txt` + AI-permissive `robots.txt` recorded) |
| Domain security | `security/klaimee-domain-security.yml` | probed (TLS 1.3, HSTS 2y, SPF + DMARC p=none, no DNSSEC, no CAA) |
