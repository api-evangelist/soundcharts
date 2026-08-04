# Soundcharts (soundcharts)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Soundcharts is a global music-market intelligence platform that aggregates standardized metadata and real-time performance data for artists, songs, albums, and playlists across streaming, social, chart, and radio sources. The Soundcharts API exposes this catalog and analytics layer over a REST interface at https://customer.api.soundcharts.com, authenticated with x-app-id and x-api-key headers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/soundcharts/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/soundcharts/refs/heads/main/apis.yml)

## Tags

- Music
- Analytics
- Market Intelligence
- Metadata
- Streaming
- Charts

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Soundcharts Artists API

Resolve and retrieve standardized artist metadata (name, country, genres, ISNI/IPI, cross-platform identifiers), related artists, current stats, and the Soundcharts score by UUID or platform identifier.

- **Human URL:** [https://developers.soundcharts.com/api/reference/artist/summary](https://developers.soundcharts.com/api/reference/artist/summary)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Artists
- Metadata
- Audience

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/artist/summary)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Soundcharts Songs API

Look up song metadata by UUID, ISRC, or platform identifier; retrieve cross-platform identifiers, audio features, chart ranks, and audience metrics.

- **Human URL:** [https://developers.soundcharts.com/api/reference/song/summary](https://developers.soundcharts.com/api/reference/song/summary)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Songs
- Metadata
- ISRC

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/song/summary)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Soundcharts Albums API

Retrieve album metadata by UUID, UPC, or platform identifier, including tracklisting, identifiers, audience, popularity, and chart ranks.

- **Human URL:** [https://developers.soundcharts.com/api/reference/album/summary](https://developers.soundcharts.com/api/reference/album/summary)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Albums
- Metadata
- UPC

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/album/summary)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Soundcharts Playlists API

Resolve playlists by UUID or platform identifier and retrieve playlist metadata and current tracklisting across streaming platforms.

- **Human URL:** [https://developers.soundcharts.com/api/reference/playlist/summary](https://developers.soundcharts.com/api/reference/playlist/summary)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Playlists
- Curation
- Tracklisting

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/playlist/summary)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Soundcharts Charts API

List song and album charts by platform and pull latest, historical, and available rankings, plus the TikTok weekly music ranking.

- **Human URL:** [https://developers.soundcharts.com/api/reference/charts/summary](https://developers.soundcharts.com/api/reference/charts/summary)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Charts
- Rankings
- TikTok

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/charts/summary)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Soundcharts Streaming and Social Metrics API

Time-series audience, follower, streaming, popularity, retention, and short-video metrics for artists, songs, and albums across streaming and social platforms.

- **Human URL:** [https://developers.soundcharts.com/api/reference/artist/get-streaming-audience](https://developers.soundcharts.com/api/reference/artist/get-streaming-audience)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Streaming
- Social
- Audience

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/artist/get-streaming-audience)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Soundcharts Radio API

Resolve radio stations by UUID or slug and retrieve artist radio spins and spin counts for airplay tracking.

- **Human URL:** [https://developers.soundcharts.com/api/reference/radio/summary](https://developers.soundcharts.com/api/reference/radio/summary)
- **Base URL:** `https://customer.api.soundcharts.com`

#### Tags

- Radio
- Airplay
- Spins

#### Properties

- [Documentation](https://developers.soundcharts.com/api/reference/radio/summary)
- [API Reference](https://developers.soundcharts.com/api/v2/doc)
- [OpenAPI](openapi/soundcharts-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/soundcharts.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/soundcharts.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/soundcharts)
- [LinkedIn](https://www.linkedin.com/company/soundcharts)
- [Website](https://soundcharts.com/)
- [Documentation](https://developers.soundcharts.com/api/v2/doc)
- [Plans](plans/soundcharts-plans-pricing.yml)
- [Rate Limits](rate-limits/soundcharts-rate-limits.yml)
- [Fin Ops](finops/soundcharts-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
