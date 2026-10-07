# Payload

> Payload — Developer infrastructure for x402, agent payments, and programmable revenue.

**PAYLOAD is the parent technology company behind Veyline, callx402, and RevRule.**

We build production infrastructure for the agent economy: the production layer for
x402 payments plus MCP, the action layer that keeps x402 working, and programmable
revenue rules. Non-custodial by design: Payload software never holds private keys
or touches funds.

- Developer portal (canonical docs): https://payloadhq.github.io/
- Commercial products: https://payloadtools.gumroad.com/
- Contact: kylers.partners@gmail.com

## Products

| Product | What it does |
|---|---|
| **Veyline by Payload** | The flagship. The production layer for x402 + MCP: autonomous economic control for paid agent operations |
| **callx402 by Payload** | Powered by Veyline. The x402 response/action layer. When x402 breaks, callx402: diagnose, rescue, route, resolve, execute — in plain language or over HTTP |
| **RevRule by Payload** | A separate product: the programmable revenue rules engine |
| **Veyline Developer Primer by Payload** | Entry/onboarding product for developers building paid x402 APIs (formerly the x402 Paid API Starter Kit) |

## Commercial products (one-time purchase)

| Product | What it does | Price |
|---|---|---|
| [Veyline Developer Primer](https://payloadtools.gumroad.com/l/x402-paid-api-starter-kit) | Drop-in Express middleware that charges AI agents per API call in USDC over the x402 protocol: 402 payment challenges, facilitator verification, usage ledger, `/.well-known/x402` manifest | $79 |
| [MCP Monetization Kit](https://payloadtools.gumroad.com/l/mcp-monetization-kit) | Per-tool-call metering for MCP servers with free quotas and USDC payment collection via x402 | $69 |
| [StableLedger](https://payloadtools.gumroad.com/l/stableledger-tax-csv) | Offline stablecoin (USDC/USDT) CSV normalizer: exchange exports to accountant-ready ledger.csv plus summary.csv | $49 |
| [n8n Reliability Guard](https://payloadtools.gumroad.com/l/n8n-agent-reliability-kit) | 10 production n8n workflows: failure alerting, timeout circuit breakers, guardrails, cost meters, eval runner | $99 |
| [MCP Launch Readiness Audit](https://payloadtools.gumroad.com/l/mcp-launch-readiness-audit) | 48-rule MCP server security/readiness scanner with fixes, hardening templates, stress-test harness, audit PDF | $79 |
| [AI Search Readiness Audit](https://payloadtools.gumroad.com/l/ai-search-readiness-audit) | Audit whether AI crawlers and search engines can access, render, and cite a website | $59 |
| [CRM Dedup System](https://payloadtools.gumroad.com/l/crm-dedup-migration-kit) | Offline CRM CSV deduplication: exact plus fuzzy duplicate review before migration | $149 |

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

## Brand notes

- Hierarchy: PAYLOAD → VEYLINE (flagship) → CALLX402 (action layer) → REVRULE (separate product) → developer products → free utilities.
- PAYLOAD is the parent company; product names always carry the endorsement: Veyline **by Payload**, callx402 **by Payload**, RevRule **by Payload**.
- callx402 is the action, not the flagship name. The flagship brand is Veyline.
- Payload is not affiliated with the x402 Foundation.

## Licensing

Free utilities are MIT (see each repo). Commercial products are single-seat
perpetual licenses, not open source; full terms ship inside each package.
