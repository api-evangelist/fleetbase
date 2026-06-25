# Fleetbase (fleetbase)

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
