# Soundcharts (soundcharts)

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
