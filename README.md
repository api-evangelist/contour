# Contour (contour)

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

A Kubernetes ingress controller using Envoy proxy that provides dynamic configuration updates and advanced routing capabilities for managing external access to services in a cluster.

**APIs.json:** [https://projectcontour.io/](https://projectcontour.io/)

## Tags

- Envoy
- Ingress Controller
- Kubernetes
- Networking
- Proxy

## Timestamps

- **Created:** 2025-01-01
- **Modified:** 2026-05-19

## APIs

### Contour HTTPProxy API

Kubernetes Custom Resource Definition that extends the standard Ingress API with advanced routing, multi-team support, TLS delegation, and weighted load balancing across multiple backend services. HTTPProxy is Contour's primary ingress configuration resource and supports inclusion of routing configuration across namespaces.

- **Human URL:** [https://projectcontour.io/docs/main/config/api/](https://projectcontour.io/docs/main/config/api/)
- **Base URL:** `https://projectcontour.io`

#### Tags

- Custom Resource
- HTTPProxy
- Ingress
- Kubernetes
- Routing

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)
- [OpenAPI](openapi/contour-httpproxy-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/contour-httpproxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-httpproxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/contour-httpproxy-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Contour Gateway API

Contour's implementation of the Kubernetes Gateway API, supporting HTTPRoute and TLSRoute resources for defining ingress traffic routing rules. Gateway API is the next-generation Kubernetes ingress standard and Contour provides support for GatewayClass, Gateway, HTTPRoute, and related resources.

- **Human URL:** [https://projectcontour.io/docs/1.30/config/gateway-api/](https://projectcontour.io/docs/1.30/config/gateway-api/)
- **Base URL:** `https://projectcontour.io`

#### Tags

- Gateway API
- Ingress
- Kubernetes
- Networking
- Routing

#### Properties

- [Documentation](https://projectcontour.io/docs/1.30/config/gateway-api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)
- [OpenAPI](openapi/contour-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/contour-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contour Kubernetes Ingress API

Contour's support for the standard Kubernetes Ingress v1 resource, enabling basic ingress use cases such as host-based and path-based routing to backend services. Contour watches Ingress v1 resources and translates them into Envoy proxy configuration, with support for IngressClass selection and Contour-specific annotations for extended configuration.

- **Human URL:** [https://projectcontour.io/docs/main/config/ingress/](https://projectcontour.io/docs/main/config/ingress/)
- **Base URL:** `https://projectcontour.io`

#### Tags

- Ingress
- Kubernetes
- Networking
- Routing
- Standard API

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/ingress/)
- [Reference](https://projectcontour.io/docs/main/config/annotations/)
- [Postman Collection](collections/contour-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/contour-httpproxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-httpproxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contour ExtensionService API

Kubernetes Custom Resource Definition for binding gRPC-based extension services to the Contour API. ExtensionService resources allow external components to implement Contour API features such as external authorization and rate limiting by registering a network service that Contour will route to via Envoy's gRPC extension protocol (v3).

- **Human URL:** [https://projectcontour.io/docs/main/config/api/](https://projectcontour.io/docs/main/config/api/)
- **Base URL:** `https://projectcontour.io`

#### Tags

- Authorization
- Custom Resource
- Extension Service
- gRPC
- Kubernetes

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)
- [Postman Collection](collections/contour-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/contour-httpproxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-httpproxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Contour Configuration API

Contour's ContourConfiguration Custom Resource Definition (v1alpha1) that provides cluster-scoped configuration of a Contour instance, including ingress settings, TLS defaults, timeouts, and feature gates. This API allows operators to declaratively manage Contour's runtime behavior through Kubernetes resources instead of command-line flags or static config files.

- **Human URL:** [https://projectcontour.io/docs/main/config/api/](https://projectcontour.io/docs/main/config/api/)
- **Base URL:** `https://projectcontour.io`

#### Tags

- Configuration
- Custom Resource
- Kubernetes
- Networking
- Operator

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)
- [Postman Collection](collections/contour-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/contour-httpproxy.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/contour-httpproxy.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://projectcontour.io/)
- [JSON-LD](json-ld/contour-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/contour-httpproxy-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Vocabulary](vocabulary/contour-vocabulary.yml)
- [Spectral Rules](rules/contour-httpproxy-rules.yml)
- [Spectral Rules](rules/contour-gateway-rules.yml)
- [Capability](capabilities/manage-httpproxy-routing.yml)
- [Capability](capabilities/configure-gateway-api-routing.yml)
- [Getting Started](https://projectcontour.io/getting-started/)
- [Documentation](https://projectcontour.io/docs/main/)
- [GitHub Organization](https://github.com/projectcontour)
- [GitHub Repository](https://github.com/projectcontour/contour)
- [Support](https://projectcontour.io/resources/support/)
- [Community](https://projectcontour.io/community/)
- [Resources](https://projectcontour.io/resources/)
- [Changelog](https://github.com/projectcontour/contour/releases)
- [Issue  Tracker](https://github.com/projectcontour/contour/issues)
- [Upgrading](https://projectcontour.io/resources/upgrading/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
