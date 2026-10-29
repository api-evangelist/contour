# Contour

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

A Kubernetes ingress controller using Envoy proxy that provides dynamic configuration updates and advanced routing capabilities for managing external access to services in a cluster.

**Areas:** Envoy · Ingress Controller · Kubernetes · Networking · Proxy

## Contour on APIs.io

Everything profiled for Contour is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/contour/](https://apis.io/providers/contour/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [Contour Kubernetes Ingress API](https://apis.io/apis/contour/contour-kubernetes-ingress-api/) — Contour's support for the standard Kubernetes Ingress v1 resource, enabling basic ingress use cases such as host-based and path-based routing to backend…
- [Contour ExtensionService API](https://apis.io/apis/contour/contour-extensionservice-api/) — Kubernetes Custom Resource Definition for binding gRPC-based extension services to the Contour API. ExtensionService resources allow external components to…
- [Contour Configuration API](https://apis.io/apis/contour/contour-configuration-api/) — Contour's ContourConfiguration Custom Resource Definition (v1alpha1) that provides cluster-scoped configuration of a Contour instance, including ingress…
- [Contour Gateway API](https://apis.io/apis/contour/contour-gateway-api/) — Namespace-scoped resources that describe network infrastructure instances that route traffic. Each Gateway is associated with a GatewayClass and defines…
- [Contour GatewayClass API](https://apis.io/apis/contour/contour-gatewayclass-api/) — Cluster-scoped resources that define the controller responsible for managing Gateways of a particular class. GatewayClass is analogous to IngressClass in…
- [Contour HTTPProxy API](https://apis.io/apis/contour/contour-httpproxy-api/) — Operations for managing Contour HTTPProxy custom resources in a Kubernetes cluster. HTTPProxy resources define ingress routing rules for HTTP and HTTPS traffic.
- [Contour HTTPRoute API](https://apis.io/apis/contour/contour-httproute-api/) — Namespace-scoped resources that define HTTP routing rules, mapping HTTP/HTTPS requests to backend Kubernetes services based on host, path, headers, and…
- [Contour TLSCertificateDelegation API](https://apis.io/apis/contour/contour-tlscertificatedelegation-api/) — Operations for managing TLSCertificateDelegation resources that allow certificates in one namespace to be used by HTTPProxy resources in other namespaces.
- [Contour TLSRoute API](https://apis.io/apis/contour/contour-tlsroute-api/) — Namespace-scoped resources that define TLS routing rules for routing TLS connections based on SNI hostname to backend services.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Contour Agentic Access](https://apis.io/agentic-access/contour/contour-agentic-access/)

#### JSON Schema (43)

The data models the API reads and writes.

- [AuthorizationServer](https://apis.io/schemas/contour/contour-authorizationserver/)
- [Condition](https://apis.io/schemas/contour/contour-condition/)
- [CORSPolicy](https://apis.io/schemas/contour/contour-corspolicy/)
- [DetailedCondition](https://apis.io/schemas/contour/contour-detailedcondition/)
- [Gateway](https://apis.io/schemas/contour/contour-gateway/)
- [GatewayClass](https://apis.io/schemas/contour/contour-gatewayclass/)
- [GatewayClassList](https://apis.io/schemas/contour/contour-gatewayclasslist/)
- [GatewayList](https://apis.io/schemas/contour/contour-gatewaylist/)
- [HeaderMatchCondition](https://apis.io/schemas/contour/contour-headermatchcondition/)
- [HeadersPolicy](https://apis.io/schemas/contour/contour-headerspolicy/)
- [HeaderValue](https://apis.io/schemas/contour/contour-headervalue/)
- [HTTPBackendRef](https://apis.io/schemas/contour/contour-httpbackendref/)
- [Contour HTTPProxy](https://apis.io/schemas/contour/contour-httpproxy/)
- [HTTPProxyList](https://apis.io/schemas/contour/contour-httpproxylist/)
- [HTTPProxySpec](https://apis.io/schemas/contour/contour-httpproxyspec/)
- [HTTPProxyStatus](https://apis.io/schemas/contour/contour-httpproxystatus/)
- [HTTPRoute](https://apis.io/schemas/contour/contour-httproute/)
- [HTTPRouteFilter](https://apis.io/schemas/contour/contour-httproutefilter/)
- [HTTPRouteList](https://apis.io/schemas/contour/contour-httproutelist/)
- [HTTPRouteMatch](https://apis.io/schemas/contour/contour-httproutematch/)
- [HTTPRouteRule](https://apis.io/schemas/contour/contour-httprouterule/)
- [Include](https://apis.io/schemas/contour/contour-include/)
- [Listener](https://apis.io/schemas/contour/contour-listener/)
- [ListenerStatus](https://apis.io/schemas/contour/contour-listenerstatus/)
- [MatchCondition](https://apis.io/schemas/contour/contour-matchcondition/)
- …and 18 more published on APIs.io

#### JSON Structure (1)

Data models expressed in JSON Structure.

- [Contour Structure](https://apis.io/json-structure/contour/contour-structure/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Contour Context](https://apis.io/jsonld/contour/contour-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Contour Ingress Vocabulary](https://apis.io/vocabularies/contour/contour-vocabulary/)

#### Collections (8)

Postman and Open Collection request collections.

- [Contour Gateway API](https://apis.io/collections/contour/open-contour-gateway/)
- [Contour Gateway API](https://apis.io/collections/contour/open-contour-gateway-api/)
- [Contour Gateway GatewayClass API](https://apis.io/collections/contour/open-contour-gatewayclass-api/)
- [Contour HTTPProxy API](https://apis.io/collections/contour/open-contour-httpproxy/)
- [Contour Gateway HTTPProxy API](https://apis.io/collections/contour/open-contour-httpproxy-api/)
- [Contour Gateway HTTPRoute API](https://apis.io/collections/contour/open-contour-httproute-api/)
- [Contour Gateway TLSCertificateDelegation API](https://apis.io/collections/contour/open-contour-tlscertificatedelegation-api/)
- [Contour Gateway TLSRoute API](https://apis.io/collections/contour/open-contour-tlsroute-api/)

#### Governance rules (3)

Spectral rulesets for the provider's contracts.

- [Contour — gateway rules](https://apis.io/rules/contour/contour-gateway-rules/)
- [Contour — httpproxy rules](https://apis.io/rules/contour/contour-httpproxy-rules/)
- [Contour — jsonschema rules](https://apis.io/rules/contour/contour-jsonschema-spectral-rules/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Contour Domain Security](https://apis.io/security/contour/contour-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Contour Plans Pricing](https://apis.io/plans/contour/contour-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Contour Rate Limits](https://apis.io/rate-limits/contour/contour-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Contour Finops](https://apis.io/finops/contour/contour-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://projectcontour.io/)
- [Documentation](https://projectcontour.io/docs/main/)
- [Getting started](https://projectcontour.io/getting-started/)
- [Support](https://projectcontour.io/resources/support/)
- [Changelog](https://github.com/projectcontour/contour/releases)
- [GitHub](https://github.com/projectcontour)

## API Evangelist rating

**Kin Score 40.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 55.4 |
| Contract quality | 54.1 |
| Contract governance | 27.3 |
| Operational transparency | 36.8 |
| Developer ergonomics | 33.3 |
| Access clarity | 5.3 |

**Agent readiness 16.6** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 10.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/contour/](https://apis.io/providers/contour/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Contour: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/contour/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
