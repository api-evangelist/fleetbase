# Fleetbase (fleetbase)

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

Fleetbase is an open-source, modular logistics and supply chain operating system (LSOS) for managing orders, drivers, vehicles, fleets, and last-mile delivery. Its RESTful API at https://api.fleetbase.io/v1 exposes orders, places, contacts, drivers, vehicles, fleets, zones, service rates, tracking, and webhooks, available both self-hosted under AGPL-3.0 and as a managed Fleetbase Cloud offering.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fleetbase/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fleetbase/refs/heads/main/apis.yml)

## Tags

- Logistics
- Fleet Management
- Supply Chain
- Last Mile Delivery
- Open Source

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Fleetbase Orders API

Create, list, update, dispatch, and cancel delivery orders with pickup and dropoff places, payloads, entities, and scheduling.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Orders
- Dispatch
- Delivery

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [API Reference](https://docs.fleetbase.io/developers/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Places API

Manage addressable places (locations) with geocoded coordinates used as pickup and dropoff points across orders.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Places
- Locations
- Geocoding

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Contacts API

Manage customer and facilitator contacts attached to orders, places, and organizations.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Contacts
- Customers

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Drivers & Vehicles API

Manage drivers and vehicles, their status, assignment to orders, and real-time location for fleet operations.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Drivers
- Vehicles
- Telematics

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Fleets & Zones API

Group drivers and vehicles into fleets and define operational service areas as zones (geofences) for dispatch and coverage.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Fleets
- Zones
- Geofences

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Service Rates API

Define service rates and rate-fee components to price orders by distance, zone, or per-drop, and generate delivery quotes.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Service Rates
- Pricing
- Quotes

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Tracking API

Retrieve tracking status, position telemetry, and tracking-number activity for orders and entities in transit.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Tracking
- Telemetry
- Real Time

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fleetbase Webhooks API

Register webhook endpoints to subscribe to order, driver, and entity lifecycle events delivered as signed HTTP callbacks.

- **Human URL:** [https://docs.fleetbase.io/api/](https://docs.fleetbase.io/api/)
- **Base URL:** `https://api.fleetbase.io/v1`

#### Tags

- Webhooks
- Events
- Notifications

#### Properties

- [Documentation](https://docs.fleetbase.io/api/)
- [OpenAPI](openapi/fleetbase-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fleetbase.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fleetbase.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/fleetbase)
- [LinkedIn](https://www.linkedin.com/company/fleetbase)
- [Website](https://www.fleetbase.io)
- [Documentation](https://docs.fleetbase.io)
- [Plans](plans/fleetbase-plans-pricing.yml)
- [Rate Limits](rate-limits/fleetbase-rate-limits.yml)
- [Fin Ops](finops/fleetbase-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
