# Allooloo Technologies Corp.

AI agent products for financial services. Allooloo runs the zones of record — the datasets agents at banks, brokerages and AI labs read when they have to show where a fact came from. Where agents read the market.

## Two products, live

**get_issuer** — the capital markets issuer record. Every listed company on twelve exchanges, every field sourced and read-dated, served in the issuer's own jurisdiction, callable by any agent over the Model Context Protocol (MCP) and the Agent-to-Agent protocol (A2A).

Door: `https://mcp.getissuer.ai/mcp` · Page: https://getissuer.ai

**Issuerwire** — agentic news coverage of the same issuers. Every filing and release as a signed row an agent can read, cite and pay for per call.

Door: `https://mcp.issuerwire.ai/mcp` · Page: https://issuerwire.ai

## The record, as of 2026-10-22

| | |
|---|---|
| Markets | 12 — Canada · United States · United Kingdom · Germany · France · Netherlands · Switzerland · Australia · Singapore · Japan · Korea · Hong Kong |
| Listed issuers on get_issuer | 31,282 |
| Disclosure events, dated and sourced | 2,576,082 |
| Issuers on Issuerwire | 26,367 |
| Signed Issuerwire rows | 1,245,839 |
| Cadence | nightly, seven nights a week, after each market's close |
| Residency | Microsoft Azure, one region per market, in-country; locked second copy on Amazon Web Services |

Counts move every night. The live figures are at https://getissuer.ai and https://issuerwire.ai/facts.json. Public-record only. No prices, no quotes, no licensed market data.

## The duty it serves

One record, twelve names for the same duty: Know Your Product (KYP) in Canada, Regulation Best Interest in the United States, product governance in the United Kingdom and the European Union, FinSA in Switzerland, the Design and Distribution Obligations in Australia, product due diligence in Singapore. An agent that recommends, approves or trades a product cites the record it read.

- **Duty doors:** agent-kyp.ai · agent-regbi.ai · agent-prod.ai · agent-mifid.ai · agent-finsa.ai · agent-ddo.ai
- **Sovereign node pages:** ca-issuer.ai · us-issuer.ai · uk-issuer.ai · de-issuer.ai · fr-issuer.ai · nl-issuer.ai · ch-issuer.ai · au-issuer.ai · sg-issuer.ai · jp-issuer.ai · kr-issuer.ai · hk-issuer.ai
- **Standards:** kyp-model.org · issuerwire.org

## The stack

MCP — how an agent calls the record. A2A — how agents hand off. x402 — how they pay per read.

Registry: `io.github.allooloo/cm-kg` · `io.github.allooloo/issuerwire`

## Repositories

- **cm-kg** — the Capital Markets Knowledge Graph (code only)
- **cm-record** — the Capital Markets Record object standard: schema, signing, versioning, resolver
- **hunter-agent** — multi-lab orchestration for the harvest, sourced and labelled per field
- **issuerwire-door** — the Issuerwire MCP door

## Keywords

AI agents financial services · capital markets knowledge graph · MCP server · Model Context Protocol · A2A · x402 · issuer record · get_issuer · Issuerwire · agentic news coverage · KYP · Regulation Best Interest · product governance · MiFID II · DDO · continuous disclosure · ISIN · LEI · listed companies dataset · investment dealer compliance · agentic fintech · zones of record

Vancouver & Toronto, Canada · https://allooloo.ai · X: https://x.com/allooloo_ai · Microsoft AI Cloud Partner
