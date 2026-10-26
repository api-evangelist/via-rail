# VIA Rail Canada (via-rail)

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

VIA Rail Canada Inc. is the federal Crown corporation that operates Canada's national intercity passenger rail network, headquartered in Montreal and reporting to Parliament through the Minister of Transport. It runs the Quebec City - Windsor corridor plus long-distance and regional services including The Canadian (Toronto - Vancouver), The Ocean (Montreal - Halifax), Winnipeg - Churchill, Jasper - Prince Rupert, Sudbury - White River, and the jointly operated Toronto - New York Maple Leaf. In the distribution chain VIA Rail is a direct-only supplier: it sells through viarail.ca, its mobile app, its call centre, and its own Travel Agency and Tour Operator portals on reservia.viarail.ca. There is no GDS channel, no NDC, no OSDM and no reseller API. VIA Rail's API posture is honestly stated as an open-standard data feed and nothing else — a real, ungated Developer Resources page offering a static GTFS schedule feed under the Open Government Licence – Canada 2.0, and no published contract whatsoever for anything transactional.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/via-rail/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/via-rail/refs/heads/main/apis.yml)

## Tags

- Travel
- Canada
- Rail
- Passenger Rail
- Transit
- GTFS
- Open Data
- Booking
- Distribution
- Travel Agents
- Crown Corporation
- Loyalty

## Timestamps

- **Created:** 2026-07-28
- **Modified:** 2026-07-28

## APIs

### VIA Rail GTFS Schedule Feed

VIA Rail's complete national timetable published as a static General Transit Feed Specification (GTFS) archive, offered for download with no registration, no API key and no rate limit. The 2026-07-09 edition covers a `20260709`-`20261107` service window and carries 19 routes, 388 stations, 85 trips, 1,577 stop times and 86,116 shape points, plus the GTFS ticketing extension files `ticketing_identifiers.txt` and `ticketing_deep_links.txt`. Downloading it binds the consumer to the Open Government Licence – Canada version 2.0, which permits commercial use subject to attribution. This is the only machine-readable contract VIA Rail publishes.

- **Human URL:** [https://www.viarail.ca/en/developer-resources](https://www.viarail.ca/en/developer-resources)
- **Base URL:** `https://www.viarail.ca/sites/all/files/gtfs/viarail.zip`

#### Tags

- GTFS
- Schedules
- Timetables
- Transit
- Open Data
- Rail

#### Properties

- [Documentation](https://www.viarail.ca/en/developer-resources)
- [GTFS](gtfs/viarail-gtfs.zip) — harvested verbatim 2026-07-28, HTTP 200, 1,010,621 bytes
- [Download](https://www.viarail.ca/sites/all/files/gtfs/viarail.zip)
- [License](https://open.canada.ca/en/open-government-licence-canada) — Open Government Licence – Canada 2.0
- [Specification](https://github.com/google/transit/blob/master/gtfs/spec/en/reference.md)
- Developer contact: `dev@viarail.ca`

## What is not published

No OpenAPI, AsyncAPI, GraphQL schema or Postman collection exists anywhere on VIA Rail's estate. The `developer.`, `developers.`, `api.`, `apis.`, `docs.` and `cdn.` subdomains of `viarail.ca` are all NXDOMAIN. Every well-known specification path on `www.viarail.ca` — `/openapi.json`, `/swagger.json`, `/api-docs`, `/api`, `/apis`, `/developer`, `/developers`, `/docs`, `/.well-known/security.txt`, `/.well-known/ai-plugin.json`, `/llms.txt` — returns 404. The Developer Resources page is reachable only at `/en/developer-resources`, and was found via the sitemap rather than by any conventional path.

Two live surfaces exist without contracts and are deliberately **excluded** from `apis.yml`:

- `https://api.reservia.viarail.ca` — an AWS API Gateway fronting the reservation platform. Resolves, answers `403 {"message":"Missing Authentication Token"}`. No documentation, no terms, no versioning policy.
- `https://tsimobile.viarail.ca/data/allData.json` — 242 KB of live train positions, speeds and bilingual alerts, public and unauthenticated, fetched by the VIA Rail Tracker. Not GTFS-Realtime, no licence, no schema, not referenced on the Developer Resources page.

**Probe warning:** `reservia.viarail.ca` is an S3-hosted SPA with a catch-all rewrite. Every path, including a nonsense control path, returns `200 text/html 3295` with ETag `"ab3cf4b8d3619361518096db7b78e2da"`. Any spec harvest that trusts a 200 from this host will fabricate results.

Full probe log, with an HTTP status for every URL, is in [review.yml](review.yml).

## Enrichment artifacts

Round 2026-07-28. Everything below is searched, probed, or derived from the harvested GTFS archive — nothing is invented. The negatives are recorded deliberately so a later round does not re-litigate them.

| Artifact | Method | What it holds |
| --- | --- | --- |
| [`json-schema/via-rail-gtfs-schema.json`](json-schema/via-rail-gtfs-schema.json) | derived | JSON Schema 2020-12 for every record in the 12 GTFS files, read off the real column headers |
| [`data-model/via-rail-data-model.yml`](data-model/via-rail-data-model.yml) | derived | 12 entities, 15 relationships, row counts, identifier domains, and what is *not* modelled (no fares) |
| [`conventions/via-rail-conventions.yml`](conventions/via-rail-conventions.yml) | derived | Transfer semantics: conditional requests via `ETag`/`Last-Modified`, `max-age=300`, UTF-8 CSV, per-stop timezones, the OGL/site-terms contradiction |
| [`authentication/via-rail-authentication.yml`](authentication/via-rail-authentication.yml) | searched | `type: none` — and that is deliberate. Plus the observed-but-unpublished Sqills OAuth grant URNs |
| [`lifecycle/via-rail-lifecycle.yml`](lifecycle/via-rail-lifecycle.yml) | searched | Dated file replacement at a stable unversioned URL. No deprecation policy, no SLA, no API status page, no changelog |
| [`conformance/via-rail-conformance.yml`](conformance/via-rail-conformance.yml) | derived | 16 standards assessed. GTFS Schedule + ticketing extension + OGL-Canada 2.0 + conditional requests + HSTS conform; OpenAPI, AsyncAPI, GraphQL, GTFS-Realtime, OSDM, RFC 9457 and RFC 9116 do not |
| [`well-known/via-rail-well-known.yml`](well-known/via-rail-well-known.yml) | searched | Every `/.well-known/` path on all five hosts. One real document estate-wide: an Apple app-site-association on the booking SPA |
| [`security/via-rail-domain-security.yml`](security/via-rail-domain-security.yml) | probed | TLSv1.2, HSTS 1y, SPF + DMARC (`quarantine`), no DNSSEC, no CAA |
| [`llms/via-rail-llms.txt`](llms/via-rail-llms.txt) | generated | `https://www.viarail.ca/llms.txt` is 404, so this is ours |

Deliberately **not** emitted, because the thing does not exist: `openapi/`, `asyncapi/`, `mcp/`, `skills/`, `packages/`, `cli/`, `sandbox/`, `components/`, `scopes/`, `errors/`, `changelog/`, `overlays/`, `grpc/`, `security/via-rail-vulnerability-disclosure.yml`, `security/via-rail-trust-center.yml`.

Registry sweep found no first-party client library on npm, PyPI, RubyGems, Packagist, crates.io, NuGet or Maven Central. The GitHub organization [`VIARailCanada`](https://github.com/VIARailCanada) is real — registered 2016-05-31, `blog: https://viarail.ca/` — and has **zero** public repositories.

## Switching Cost

The point of this profile. Summarised from the `switchingCost` block in [review.yml](review.yml).

| Dimension | Finding |
| --- | --- |
| Interface shape | `open-standard` — GTFS static plus the GTFS ticketing extension, licensed OGL-Canada 2.0. Scoped to schedules only; the transactional surface is none-published |
| Second source | `no-alternative` — VIA is the only route to a VIA seat; but the *schedule data* is trivially portable because GTFS is a commodity format |
| Exit path | `export-on-request` — an Access to Information / Privacy Act request to a federal Crown corporation. No export operation exists because no transactional API exists |
| Identifier portability | Portable on the published side (GTFS `stop_id`, four-letter station mnemonics, VIA train numbers, `ticketing_trip_id` `VIA87`), proprietary on the commercial side (8-digit tour-operator account numbers, VIA Préférence numbers) |
| Contractual lock-in | Published, and self-contradictory — see below |
| Distribution model | `direct-only` — no GDS is named anywhere on the site |
| NDC posture | Not applicable (rail). The rail analogue, UIC OSDM, is also never referenced — even though the PSS carries UIC station codes |
| Access gate | `self-serve` for the GTFS. `application-approval` for anything transactional |

### The one genuinely generous thing

VIA Rail hands a developer a complete national rail timetable with no account, no key, no click-through and no rate limit, under a licence that explicitly permits commercial reuse:

> "You are free to: Copy, modify, publish, translate, adapt, distribute or otherwise use the Information in any medium, mode or format for any lawful purpose." — Open Government Licence – Canada 2.0

That is a genuinely open contract, and there is almost nothing else like it in Canadian travel.

### The contradiction VIA never resolves

The GTFS file is served from `www.viarail.ca` — which is "the Site" — and the Site's own Terms of Use say the opposite:

> "Use of the Site for any other purpose, including for illegal purposes or purposes that are contrary to the Terms and **for commercial purposes**, is strictly prohibited."

A commercial integrator is relying on the narrower file-scoped licence overriding the broader site terms. VIA has not written that reconciliation down anywhere.

### What it costs to actually sell a VIA ticket

- A travel agency must hold and register an **agency IATA number**, be "approved as an individual agency or registered under a preferred partner agreement", nominate an administrator, then register each agent — all through an Agency Support desk, with **no agreement published to read in advance**.
- A tour operator must "demonstrate a plan to earn and maintain a **minimum revenue of $25,000/year**" and "combine rail tickets with other tour components in travel packages." **"VIA Rail tickets must not be sold on their own and outside of packaged travel."** They receive a proprietary 8-digit account number.
- Both then transact through a **human web sign-in** at `reservia.viarail.ca`. There is no API to call at any price.
- Site Terms of Use additionally forbid reverse engineering and derivative works, cap VIA's liability at **CAD $250**, allow amendment at any time by posting, and put every dispute in the courts of Montreal, Quebec.

### The stack, which VIA does not talk about

The reservation platform is **Sqills S3 Passenger** — OAuth grant types `https://com.sqills.s3.oauth.public`, `.booking` and `.agent`, plus RFC 8693 token exchange — integrated by **CGI**, fronted by AWS API Gateway and CloudFront. The booking front end reads `_u_i_c_station_code` off every segment, meaning the UIC identifiers that would make standards-based rail distribution possible are physically present in the stack. None of it is published, certified or offered to partners. The travel-agent FAQ confirms it is new: *"Yes, our new reservation system has now launched!"*

## Properties

- [Website](https://www.viarail.ca/en)
- [Developer Resources](https://www.viarail.ca/en/developer-resources) — [French](https://www.viarail.ca/fr/ressources-developpeurs)
- [Corporate](https://corpo.viarail.ca/en)
- [Media room](https://media.viarail.ca/en)
- [Travel Agency Portal](https://reservia.viarail.ca/en/booking/agent/login)
- [Business Partner Portal](https://reservia.viarail.ca/en/booking/contra/login)
- [Travel Agency Registration](https://www.viarail.ca/en/travel-agents/travel-agent-registration)
- [Tour Operator Registration](https://www.viarail.ca/en/travel-agents/tour-operator-registration)
- [Travel Agent FAQ](https://www.viarail.ca/en/travel-agents/travel-agent-faq)
- [Tour Operator FAQ](https://www.viarail.ca/en/travel-agents/tour-operator-faq)
- [AD75 Terms and Conditions](https://www.viarail.ca/en/travel-agents/ad75-conditions)
- [Terms of Use of the Site](https://www.viarail.ca/en/terms-and-conditions)
- [Conditions of the contract](https://www.viarail.ca/en/conditions-contract)
- [Privacy Policy](https://www.viarail.ca/en/our-privacy-policy)
- [Open Government Licence – Canada 2.0](https://open.canada.ca/en/open-government-licence-canada)
- [Governance & Ethics / Access to Information](https://corpo.viarail.ca/en/company/governance-ethics)
- [Access to Information Request Form](https://www.viarail.ca/sites/all/files/media/pdfs/access-to-information/en_entr_access_info_form.pdf)
- [VIA Préférence](https://www.viapreference.com/en/home)
- [Booking engine](https://reservia.viarail.ca/)
- [VIA Rail Tracker](https://tsimobile.viarail.ca/)
- [Blog](https://www.viarail.ca/en/blog)
- [Careers](https://careers.viarail.ca/?locale=en_US)
- [LinkedIn](https://www.linkedin.com/company/via-rail-canada)

## Maintainers

- Kin Lane — kin@apievangelist.com
