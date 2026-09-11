# Allooloo Technologies Corp.
**Agentic Capital Markets Tools.** The Capital Markets Knowledge Graph (CM-KG), served live to AI agents over the Model Context Protocol. Canada first.

## Canada's equity market, mapped for agents
On September 10, 2026, Allooloo ran the whole Canadian listed market through machines and recorded what answered.

| | |
|---|---|
| Listed securities — TSX, TSXV, CSE, Cboe Canada | **4,820** |
| Corporate issuers | **2,851** |
| Disclosure events, 12-month window, each dated and URL'd | **25,222** |
| Legal Entity Identifiers resolved on a strict rule | **3,283** |
| Sourced issuer aliases — no guesses | **682** |
| Frontier engines with a named duty | **8** |
| Passes per field — harvest, fill, confirm | **3** |

Every field names the registry it came from or the engine that read it, and carries a state: sourced, filled, confirmed, or conflict. Public-record only. No prices, no quotes, no licensed market data.

## What refused to answer
The plumbing of Canadian capital markets is pre-agentic. Read from the wire, not the brochure:
- SEDAR+ and SEDI answer HTTP 403 to machines; no per-issuer URL exists on SEDI
- CIRO halt notices: 403; CDS corporate-action bulletins: behind the participant login
- TSX senior-issuer bulletins: no public per-issuer list; Cboe Canada notices: unreadable, bulletins by subscription
- No Canadian exchange publishes ISINs; TSXV tier and Cboe sector are published nowhere
- GLEIF's ISIN-to-LEI mapping (9.25M rows) contains zero Canadian-prefixed ISINs

That is not a coverage gap. It is the absence of a layer. This is the layer.

## The record
**Capital Markets Record (CMR)** — one per listed company, keyed on ISIN, ticker and LEI. Versioned, sourced, never deleted. Built for the duty every dealer carries on every name it shelves: KYP in Canada, product governance in London and Frankfurt, reasonable-basis suitability in New York, DDO in Sydney, product due diligence in Singapore. Same record, twelve names.

## The graph
Issuers as nodes. Insiders across boards, holders across names, shared auditors and transfer agents, parents and subsidiaries, dual listings across markets, the newswire each issuer actually uses. Twelve sovereign market nodes, one door:
Canada · United Kingdom · Australia · Singapore · Switzerland · Germany · France · Netherlands · Hong Kong · Japan · South Korea · United States

## The orchestra
Eight engines, named duties, human cut. Claude adjudicates. ChatGPT extracts at scale. Gemini reads the whole filing. Perplexity grounds the cold read. Grok hears the wire first. Mistral reads Montréal in French and Frankfurt in German. Tavily is the net. Cloudflare is the network. Compute on Microsoft Azure; the Google Cloud AI stack deployed as it ships.

## Repositories
- **cm-kg** — the Capital Markets Knowledge Graph
- **cm-record** — the CMR object standard: schema, signing, versioning, resolver
- **hunter-agent** — multi-lab orchestration for the harvest, sourced and labelled per field

## For agents
Doors open here as they answer. None is listed before it does.

## Keywords
capital markets knowledge graph · MCP server · Model Context Protocol · AI agents finance · agentic capital markets · issuer record · Capital Markets Record · KYP · product governance · continuous disclosure · ISIN · LEI · SEDAR+ · TSX · TSXV · CSE · listed companies dataset · investment dealer compliance · Canada · Bay Street · agentic fintech

Vancouver, Canada · https://allooloo.io · **2027, today.**
