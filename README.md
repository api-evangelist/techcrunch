# TechCrunch (techcrunch)

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
