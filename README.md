# Radio.co (radio-co)

Your toolset for creating bespoke players. Showcase your station to fit your website, apps, and beyond.

**APIs.yml URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/radio-co/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- Radio
- Streaming
- Audio
- Music

## Timestamps

- **Created:** 2025-02-12
- **Modified:** 2026-04-28

## APIs

### Radio.co

Public Radio.co API for retrieving station status, metadata, and currently-playing track information.

- **Documentation:** https://radio.co/api
- **Base URL:** `https://public.radio.co`
- **OpenAPI:** [openapi/radio-co-openapi.yml](openapi/radio-co-openapi.yml)
- **Authentication:** Publicly accessible (no auth documented)

#### Endpoints

- `GET /stations/{stationId}/status` — Track history, bitrate, and full station status
- `GET /api/v2/{stationId}` — Station name, logo, and stream URL
- `GET /api/v2/{stationId}/track/current` — Currently playing track, start time, artwork

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
