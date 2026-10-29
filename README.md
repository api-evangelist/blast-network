# Blast

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Blast is an Ethereum Layer 2 network (OP Stack-derived, post-Pacific Meridian upgrade) that pays native yield on bridged ETH and stablecoins via auto- rebasing tokens — roughly 4% on ETH (from Ethereum staking) and 5% on USDB (from T-Bill protocols) — and programmatically returns a share of net gas revenue to dApps. Mainnet runs at chain ID 81457 with public JSON-RPC at rpc.blast.io and a Sepolia testnet at chain ID 168587773 / sepolia.blast.io. Developer surfaces include Blastscan and Sepolia Blastscan explorers, the native bridge, USDB stablecoin, and the gas / yield smart contracts.

**Areas:** Blockchain · Layer 2 · Ethereum · EVM · Native Yield · Rebasing · OP Stack

## Blast on APIs.io

Everything profiled for Blast is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/blast-network/](https://apis.io/providers/blast-network/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Blast Mainnet JSON-RPC](https://apis.io/apis/blast-network/mainnet-rpc/) — Public Ethereum-compatible JSON-RPC endpoint for Blast mainnet (chain ID 81457). Supports the standard eth_* method set used by web3 clients, wallets, and…
- [Blast Sepolia Testnet JSON-RPC](https://apis.io/apis/blast-network/sepolia-rpc/) — Public JSON-RPC endpoint for the Blast Sepolia testnet (chain ID 168587773), used for application development, integration testing, and bridge testing…
- [Blast Native Yield Contracts](https://apis.io/apis/blast-network/native-yield/) — Auto-rebasing yield mechanism for ETH and USDB on Blast. Contracts expose configuration calls to opt accounts into automatic, claimable, or void yield…
- [Blast Gas Revenue API](https://apis.io/apis/blast-network/gas-revenue/) — Programmatic interface for dApps to claim back a share of the net gas revenue generated by their contracts on Blast, configured per-contract via the Blast…
- [USDB Native Stablecoin](https://apis.io/apis/blast-network/usdb-stablecoin/) — USDB is Blast's native auto-rebasing stablecoin, redeemable 1:1 for DAI when bridged back to Ethereum. Backed by T-Bill protocols and integrated directly…
- [Blast Bridge](https://apis.io/apis/blast-network/bridge/) — Canonical Ethereum-Blast bridge for ETH, USDB, and supported ERC-20 tokens. UI lives at bridge.blast.io and is backed by the OP Stack standard bridge contracts.
- [Blastscan Block Explorer](https://apis.io/apis/blast-network/blastscan-explorer/) — Etherscan-style block explorer for Blast mainnet — transactions, blocks, addresses, contracts, tokens, and Solidity source verification.
- [Blastscan Sepolia Testnet Explorer](https://apis.io/apis/blast-network/blastscan-sepolia-explorer/) — Blastscan instance for the Blast Sepolia testnet, supporting transaction lookup and contract verification for testnet deployments.
- [Blast JSON-RPC API](https://apis.io/apis/blast-network/blast-network-json-rpc-api/) — Ethereum-compatible JSON-RPC methods exposed by the Blast node.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Blast Network Agentic Access](https://apis.io/agentic-access/blast-network/blast-network-agentic-access/)

#### Collections (2)

Postman and Open Collection request collections.

- [Blast Network JSON-RPC](https://apis.io/collections/blast-network/open-blast-network/)
- [Blast Network JSON-RPC API](https://apis.io/collections/blast-network/open-blast-network-json-rpc-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Blast Network Domain Security](https://apis.io/security/blast-network/blast-network-domain-security/)
- [Blast Network Vulnerability Disclosure](https://apis.io/security/blast-network/blast-network-vulnerability-disclosure/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Blast Network Plans Pricing](https://apis.io/plans/blast-network/blast-network-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Blast Network Rate Limits](https://apis.io/rate-limits/blast-network/blast-network-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Blast Network Finops](https://apis.io/finops/blast-network/blast-network-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://blast.io)
- [Documentation](https://docs.blast.io)
- [Getting started](https://docs.blast.io/building/network-information)
- [API reference](https://docs.blast.io/building/network-information)
- [Blog](https://blog.blast.io)
- [Terms of service](https://blast.io/terms)
- [Privacy policy](https://blast.io/privacy)

## API Evangelist rating

**Kin Score 27.5** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 47.1 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 35.7 |
| Access clarity | 5.3 |

**Agent readiness 20.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/blast-network/](https://apis.io/providers/blast-network/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Blast: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/blast-network/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
