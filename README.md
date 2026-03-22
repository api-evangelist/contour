# Contour ()
A Kubernetes ingress controller using Envoy proxy that provides dynamic configuration updates and advanced routing capabilities for managing external access to services in a cluster.

**URL:** [Visit APIs.json URL](https://projectcontour.io/)

## Tags:

 - Kubernetes, Ingress Controller, Envoy, Proxy, Networking

## Timestamps

- **Created:** 2025-01-01 
- **Modified:** 2026-03-18 

## APIs

### Contour HTTPProxy API
Kubernetes Custom Resource Definition that extends the standard Ingress API with advanced routing, multi-team support, TLS delegation, and weighted load balancing across multiple backend services. HTTPProxy is Contour's primary ingress configuration resource and supports inclusion of routing configuration across namespaces.

**Human URL:** [https://projectcontour.io/docs/main/config/api/](https://projectcontour.io/docs/main/config/api/)


#### Tags:

 - Kubernetes, Ingress, HTTPProxy, Routing, Custom Resource

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)
- [OpenAPI](openapi/contour-httpproxy-openapi.yml)
- [JSONSchema](json-schema/contour-httpproxy-schema.json)

### Contour Gateway API
Contour's implementation of the Kubernetes Gateway API, supporting HTTPRoute and TLSRoute resources for defining ingress traffic routing rules. Gateway API is the next-generation Kubernetes ingress standard and Contour provides support for GatewayClass, Gateway, HTTPRoute, and related resources.

**Human URL:** [https://projectcontour.io/docs/1.30/config/gateway-api/](https://projectcontour.io/docs/1.30/config/gateway-api/)


#### Tags:

 - Kubernetes, Gateway API, Ingress, Routing, Networking

#### Properties

- [Documentation](https://projectcontour.io/docs/1.30/config/gateway-api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)
- [OpenAPI](openapi/contour-gateway-openapi.yml)

### Contour Kubernetes Ingress API
Contour's support for the standard Kubernetes Ingress v1 resource, enabling basic ingress use cases such as host-based and path-based routing to backend services. Contour watches Ingress v1 resources and translates them into Envoy proxy configuration, with support for IngressClass selection and Contour-specific annotations for extended configuration.

**Human URL:** [https://projectcontour.io/docs/main/config/ingress/](https://projectcontour.io/docs/main/config/ingress/)


#### Tags:

 - Kubernetes, Ingress, Routing, Networking, Standard API

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/ingress/)
- [Reference](https://projectcontour.io/docs/main/config/annotations/)

### Contour ExtensionService API
Kubernetes Custom Resource Definition for binding gRPC-based extension services to the Contour API. ExtensionService resources allow external components to implement Contour API features such as external authorization and rate limiting by registering a network service that Contour will route to via Envoy's gRPC extension protocol (v3).

**Human URL:** [https://projectcontour.io/docs/main/config/api/](https://projectcontour.io/docs/main/config/api/)


#### Tags:

 - Kubernetes, Extension Service, gRPC, Custom Resource, Authorization

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)

### Contour Configuration API
Contour's ContourConfiguration Custom Resource Definition (v1alpha1) that provides cluster-scoped configuration of a Contour instance, including ingress settings, TLS defaults, timeouts, and feature gates. This API allows operators to declaratively manage Contour's runtime behavior through Kubernetes resources instead of command-line flags or static config files.

**Human URL:** [https://projectcontour.io/docs/main/config/api/](https://projectcontour.io/docs/main/config/api/)


#### Tags:

 - Kubernetes, Configuration, Custom Resource, Operator, Networking

#### Properties

- [Documentation](https://projectcontour.io/docs/main/config/api/)
- [Reference](https://projectcontour.io/docs/main/config/api-reference.html)

## Common Properties

- [Website](https://projectcontour.io/)
- [JSON-LD](json-ld/contour-context.jsonld)
- [JSONSchema](json-schema/contour-httpproxy-schema.json)
- [Getting Started](https://projectcontour.io/getting-started/)
- [Documentation](https://projectcontour.io/docs/main/)
- [GitHub Organization](https://github.com/projectcontour)
- [GitHubRepository](https://github.com/projectcontour/contour)
- [Support](https://projectcontour.io/resources/support/)
- [Community](https://projectcontour.io/community/)
- [Resources](https://projectcontour.io/resources/)
- [Change Log](https://github.com/projectcontour/contour/releases)
- [Issue Tracker](https://github.com/projectcontour/contour/issues)
- [Upgrading](https://projectcontour.io/resources/upgrading/)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
