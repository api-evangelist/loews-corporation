# Loews Corporation

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
