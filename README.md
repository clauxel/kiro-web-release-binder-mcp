# Kiro Web Release Binder MCP

Turn Kiro-generated work into release evidence agents can trust.

Kiro Web Release Binder is a paid remote MCP release gate for Kiro projects, release goals, acceptance criteria, owner signoff, evidence binders, and CI-friendly approval receipts.

This is a public documentation project for Kiro Web Release Binder MCP. The structure is modeled after the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and public-safe architecture notes.

## Start Here

- Website: https://kirowebreleasebinder.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=kirowebreleasebinder_public_docs&utm_content=readme_primary_home
- Pricing: https://kirowebreleasebinder.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=kirowebreleasebinder_public_docs&utm_content=readme_pricing
- Checkout: https://kirowebreleasebinder.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=kirowebreleasebinder_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://kirowebreleasebinder.clauxel.com/mcp
- Server card: https://kirowebreleasebinder.clauxel.com/server-card.json
- Registry name: `com.clauxel.kirowebreleasebinder/kirowebreleasebinder-mcp`
- Tools: `check_kiro_release_readiness`, `collect_release_evidence`, `request_owner_signoff`, `issue_release_receipt`, `export_release_binder`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Public link reference](reference/links.md)

## Audience

AI IDE teams, delivery leads, release managers, and client-service studios.

## Capabilities

- release policy rules
- Kiro project intake
- evidence checklist
- owner signoff
- tool-call receipts

## Public-Safe Boundary

This repository does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
