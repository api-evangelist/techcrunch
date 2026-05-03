# TechCrunch

TechCrunch (https://techcrunch.com/) is a leading technology media property dedicated
to covering startups, venture capital, and innovation. Founded in 2005 and acquired
by AOL in 2010 and later by Yahoo, TechCrunch delivers breaking news, in-depth analysis,
and original reporting on the technology industry, emerging companies, funding rounds,
and the people shaping the future of tech. The publication hosts flagship events
including TechCrunch Disrupt and the Startup Battlefield competition. TechCrunch is
built on WordPress and exposes the standard WordPress REST API for programmatic content
access, as well as RSS feeds for content syndication.

**Website:** https://techcrunch.com/  
**WordPress REST API Docs:** https://developer.wordpress.org/rest-api/  
**RSS Feed:** https://techcrunch.com/feed/

## Tags

Media, News, Startups, Technology News, Venture Capital

## Timestamps

- **Created:** 2026-03-24
- **Modified:** 2026-05-03

## APIs

### TechCrunch WordPress REST API

TechCrunch exposes the standard WordPress REST API at `https://techcrunch.com/wp-json/wp/v2`.
No authentication required for read operations. Supports filtering, pagination, searching,
and sorting across all content types.

**Base URL:** `https://techcrunch.com/wp-json/wp/v2`

**Endpoints:**
- Posts: `GET /posts`, `GET /posts/{id}`
- Pages: `GET /pages`, `GET /pages/{id}`
- Categories: `GET /categories`, `GET /categories/{id}`
- Tags: `GET /tags`, `GET /tags/{id}`
- Authors: `GET /users`, `GET /users/{id}`
- Media: `GET /media`, `GET /media/{id}`
- Comments: `GET /comments`, `GET /comments/{id}`
- Search: `GET /search?search={query}`

### TechCrunch RSS Feed

Standard RSS/Atom feeds available at `https://techcrunch.com/feed/` covering all published
articles. Category-specific feeds available for startups, VC, AI, security, and more.

## Artifacts

| Type | File |
|---|---|
| OpenAPI | [techcrunch-wordpress-rest-api-openapi.yml](openapi/techcrunch-wordpress-rest-api-openapi.yml) |
| Spectral Rules | [techcrunch-wordpress-rules.yml](rules/techcrunch-wordpress-rules.yml) |
| Capabilities (Shared) | [shared/wordpress-rest-api.yaml](capabilities/shared/wordpress-rest-api.yaml) |
| Workflow Capability | [content-discovery.yaml](capabilities/content-discovery.yaml) |
| JSON Schema (Post) | [techcrunch-post-schema.json](json-schema/techcrunch-post-schema.json) |
| JSON Schema (Category) | [techcrunch-category-schema.json](json-schema/techcrunch-category-schema.json) |
| JSON Structure (Post) | [techcrunch-post-structure.json](json-structure/techcrunch-post-structure.json) |
| JSON-LD Context | [techcrunch-context.jsonld](json-ld/techcrunch-context.jsonld) |
| Examples | [techcrunch-list-posts-example.json](examples/techcrunch-list-posts-example.json) |
| Examples | [techcrunch-search-example.json](examples/techcrunch-search-example.json) |
| Vocabulary | [techcrunch-vocabulary.yml](vocabulary/techcrunch-vocabulary.yml) |

## Capabilities

### Workflow Capabilities

- **[Content Discovery](capabilities/content-discovery.yaml)** - Unified REST + MCP capability for article retrieval, category/tag browsing, author profiles, and full-text search (8 tools).

### Shared Per-API Definitions

- **[WordPress REST API](capabilities/shared/wordpress-rest-api.yaml)** - Complete consumed definition for the TechCrunch WordPress REST API.

## Common Properties

- [Website](https://techcrunch.com/)
- [About](https://techcrunch.com/about-techcrunch/)
- [Newsletter](https://techcrunch.com/newsletters/)
- [RSS Feeds](https://techcrunch.com/feed/)
- [Advertising](https://techcrunch.com/advertise/)
- [Contact](https://techcrunch.com/contact-us/)
- [Terms of Service](https://techcrunch.com/terms-of-service/)
- [Privacy Policy](https://techcrunch.com/privacy-policy/)
- [X](https://x.com/TechCrunch)
- [LinkedIn](https://www.linkedin.com/company/techcrunch/)
- [Facebook](https://www.facebook.com/techcrunch/)
- [Instagram](https://www.instagram.com/techcrunch/)

## Maintainers

- Kin Lane (kin@apievangelist.com)
