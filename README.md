# Payload

**Payload** builds small, sharp tools for developers: per-call API monetization,
MCP server tooling, n8n reliability kits, and offline data utilities.
One-time pricing. No subscriptions. Non-custodial by design — Payload software
never holds private keys or touches funds.

- Developer portal: https://payloadhq.github.io/
- Products: https://payloadtools.gumroad.com/
- Contact: kylers.partners@gmail.com

## Commercial products (one-time purchase)

| Product | What it does | Price |
|---|---|---|
| [x402 Paid API Starter Kit](https://payloadtools.gumroad.com/l/x402-paid-api-starter-kit) | Drop-in Express middleware that charges AI agents per API call in USDC over the x402 protocol: 402 payment challenges, facilitator verification, usage ledger, `/.well-known/x402` manifest | $79 |
| [MCP Monetization Kit](https://payloadtools.gumroad.com/l/mcp-monetization-kit) | Per-tool-call metering for MCP servers with free quotas and USDC payment collection via x402 | $69 |
| [StableLedger](https://payloadtools.gumroad.com/l/stableledger-tax-csv) | Offline stablecoin (USDC/USDT) CSV normalizer: exchange exports → accountant-ready ledger.csv + summary.csv | $49 |
| [n8n Production AI Agent Reliability Kit](https://payloadtools.gumroad.com/l/n8n-agent-reliability-kit) | 10 production n8n workflows: failure alerting, timeout circuit breakers, guardrails, cost meters, eval runner | $99 |
| [MCP Launch Readiness Audit](https://payloadtools.gumroad.com/l/mcp-launch-readiness-audit) | 48-rule MCP server security/readiness scanner with fixes, hardening templates, stress-test harness, audit PDF | $79 |
| [AI Search Readiness Audit](https://payloadtools.gumroad.com/l/ai-search-readiness-audit) | Audit whether AI crawlers and search engines can access, render, and cite a website | $59 |
| [CRM Dedup & Migration Cleanup Kit](https://payloadtools.gumroad.com/l/crm-dedup-migration-kit) | Offline CRM CSV deduplication: exact + fuzzy duplicate review before migration | $149 |

## Free utilities (MIT)

| Repo | What it does |
|---|---|
| [mcp-manifest-validator](https://github.com/Payloadhq/mcp-manifest-validator) | Validate an MCP `server.json` manifest: required fields, name format, semver, transport |
| [n8n-workflow-linter](https://github.com/Payloadhq/n8n-workflow-linter) | Static lint for n8n workflow JSON: missing error handling, timeouts, hardcoded secrets |
| [csv-duplicate-inspector](https://github.com/Payloadhq/csv-duplicate-inspector) | Inspect a CSV for duplicate risk: exact rows, key-column dupes, near-dupes; streams large files |
| [mcp-readiness-check](https://github.com/Payloadhq/mcp-readiness-check) | GitHub Action: 10 MCP server readiness checks on every PR |
| [payload-sample-mcp-server](https://github.com/Payloadhq/payload-sample-mcp-server) | Installable sample MCP server demonstrating per-tool-call free-quota metering |

## Free samples (limited demos of paid kits)

| Repo | What it does |
|---|---|
| [mcp-monetization-demo](https://github.com/Payloadhq/mcp-monetization-demo) | Runnable demo of per-tool-call metering with free quota (hard-capped, in-memory) |
| [n8n-reliability-free-samples](https://github.com/Payloadhq/n8n-reliability-free-samples) | 2 of the 10 n8n reliability workflows, fully standalone |

## Licensing

Free utilities are MIT (see each repo). Commercial products are single-seat
perpetual licenses — not open source; full terms ship inside each package.
