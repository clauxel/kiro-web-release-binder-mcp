# Kiro Web Release Binder MCP

Turn Kiro-generated work into release evidence agents can trust.

Paid remote MCP for Kiro release readiness checks, evidence binders, owner signoff, release receipts, and CI approval gates.

## Public Endpoints

- Website: https://kirowebreleasebinder.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://kirowebreleasebinder.clauxel.com/mcp
- Server card: https://kirowebreleasebinder.clauxel.com/server-card.json
- Registry name: `com.clauxel.kirowebreleasebinder/kirowebreleasebinder-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `check_kiro_release_readiness`
- `collect_release_evidence`
- `request_owner_signoff`
- `issue_release_receipt`
- `export_release_binder`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://kirowebreleasebinder.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://kirowebreleasebinder.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://kirowebreleasebinder.clauxel.com/server-card.json
- MCP endpoint: https://kirowebreleasebinder.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
