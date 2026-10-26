# TechCrunch (techcrunch)

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

TechCrunch (https://techcrunch.com/) is a leading technology media property dedicated to covering startups, venture capital, and innovation. Founded in 2005 and acquired by AOL in 2010 and later by Yahoo, TechCrunch delivers breaking news, in-depth analysis, and original reporting on the technology industry, emerging companies, funding rounds, and the people shaping the future of tech. The publication hosts flagship events including TechCrunch Disrupt and the Startup Battlefield competition. TechCrunch runs on WordPress and exposes the standard WordPress REST API for programmatic content access.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Media
- News
- Startups
- Technology News
- Venture Capital

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-19

## APIs

### TechCrunch WordPress REST API

TechCrunch is built on WordPress and exposes the standard WordPress REST API, providing JSON endpoints for accessing posts, pages, categories, tags, authors, media, comments, and search. The API is available at the /wp-json/wp/v2/ base path and supports filtering, pagination, searching, and sorting across all TechCrunch content. TechCrunch uses a headless WordPress architecture with a React frontend, making the REST API the primary data layer for content delivery. No authentication is required for read operations.

- **Human URL:** [https://developer.wordpress.org/rest-api/](https://developer.wordpress.org/rest-api/)
- **Base URL:** `https://techcrunch.com/wp-json/wp/v2`

#### Tags

- Content
- JSON
- Media
- REST
- WordPress

#### Properties

- [Documentation](https://developer.wordpress.org/rest-api/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/openapi/techcrunch-wordpress-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-schema/techcrunch-post-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Naftiko P Capabilities](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/capabilities/content-discovery.yaml)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/rules/techcrunch-wordpress-rules.yml)
- [Postman Collection](collections/techcrunch-wordpress-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/techcrunch-wordpress-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TechCrunch RSS Feed

TechCrunch provides RSS feeds covering its full range of technology news, startup coverage, and venture capital reporting. The main feed delivers all published articles, and category-specific feeds are available for topics including startups, venture capital, artificial intelligence, security, apps, gadgets, and more. These standard RSS/Atom feeds allow readers and developers to consume TechCrunch content programmatically using any standard feed reader or parsing library.

- **Human URL:** [https://techcrunch.com/feed/](https://techcrunch.com/feed/)
- **Base URL:** `https://techcrunch.com`

#### Tags

- Feed
- News
- RSS
- Syndication

#### Properties

- [Documentation](https://techcrunch.com/feed/)
- [R S S Feed](https://techcrunch.com/feed/)
- [Postman Collection](collections/techcrunch-wordpress-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/techcrunch-wordpress-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/techcrunch)
- [Website](https://techcrunch.com/)
- [About](https://techcrunch.com/about-techcrunch/)
- [Newsletter](https://techcrunch.com/newsletters/)
- [R S S Feeds](https://techcrunch.com/feed/)
- [Advertising](https://techcrunch.com/advertise/)
- [Contact](https://techcrunch.com/contact-us/)
- [Terms of Service](https://techcrunch.com/terms-of-service/)
- [Privacy Policy](https://techcrunch.com/privacy-policy/)
- [X (Twitter)](https://x.com/TechCrunch)
- [LinkedIn](https://www.linkedin.com/company/techcrunch/)
- [Facebook](https://www.facebook.com/techcrunch/)
- [Instagram](https://www.instagram.com/techcrunch/)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/vocabulary/techcrunch-vocabulary.yml)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/techcrunch/refs/heads/main/json-ld/techcrunch-context.jsonld)
- [Integrations](https://techcrunch.com/category/apps/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
