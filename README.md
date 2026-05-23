# Loews Corporation

> "Loews is focused on long-term value creation for its shareholders, and conservative financial management."
> — Loews Corporation, Investor Relations

Loews Corporation (NYSE: **L**) is a diversified holding company headquartered
in New York City and controlled by the Tisch family. It does not itself
publish developer APIs; instead, it allocates capital across four operating
subsidiaries. This repository catalogs the portfolio so that downstream API
Evangelist research can hop from the parent to each operating company's own
developer (or non-developer) surface.

## Portfolio

| Subsidiary | Sector | Ownership | URL |
|---|---|---|---|
| **CNA Financial Corporation** (NYSE: CNA) | Commercial P&C Insurance | ~92% | https://www.cna.com/ |
| **Boardwalk Pipelines** | Midstream Energy / Natural Gas | 100% | https://bwpipelines.com/ |
| **Loews Hotels & Co** | Hospitality (~27 properties) | 100% | https://www.loewshotels.com/ |
| **Altium Packaging** | Rigid Plastic Packaging (65+ plants) | ~99% | https://www.altiumpkg.com/ |

## API Surface

**Zero public APIs.** Loews Corporation is a pure holding company. Public
artifacts are SEC filings, press releases, and investor-relations materials —
served via Q4 Inc.'s standard IR site stack. Operating subsidiaries each have
their own posture:

- **CNA Financial** — agent portals (CNA Central, eSight, Agent Center,
  Beyond HR, Cardinal E&S, CNA Surety). No public developer program.
- **Boardwalk Pipelines** — FERC-style Electronic Bulletin Board /
  Informational Postings; no REST API.
- **Loews Hotels** — branded reservations system; no public booking API.
- **Altium Packaging** — product catalog and quote-request form; no API.

## Files in this repository

- [`apis.yml`](./apis.yml) — APIs.yml 0.20 index of the parent and its
  portfolio companies, with all known public surfaces enumerated.
- `README.md` — this file.

## Why no specs?

Per the API Evangelist pipeline rule, artifacts (`openapi/`, `asyncapi/`,
`json-schema/`, `capabilities/`, `rules/`, etc.) are **only** generated when
real, citable upstream content exists. Loews Corporation publishes none, so
none are fabricated here. If/when a subsidiary's public developer surface
appears (e.g., a CNA partner API portal, a Loews Hotels booking API), it
should be indexed in its **own** dedicated `api-evangelist/<subsidiary>`
repository — not synthesized under the parent.

## Sources

- https://www.loews.com/
- https://www.loews.com/investors
- https://www.cna.com/
- https://bwpipelines.com/
- https://www.loewshotels.com/
- https://www.altiumpkg.com/

---

Part of the [API Evangelist Network](https://github.com/api-evangelist).
Maintained by [Kin Lane](https://apievangelist.com).
