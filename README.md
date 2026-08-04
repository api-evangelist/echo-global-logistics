# Echo Global Logistics (echo-global-logistics)

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

Echo Global Logistics is a third-party logistics (3PL) provider and freight brokerage offering multimodal transportation (full truckload, LTL, partial, intermodal rail, air and ocean, drayage) and managed transportation technology. Echo was taken private by The Jordan Company in June 2021 for $1.3B. Its technology platform spans EchoShip (shipper portal), EchoDrive (carrier portal and mobile app), EchoConnect (broker architecture) and EchoSync, the API and EDI integration platform.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/echo-global-logistics/refs/heads/main/apis.yml)

## Type
- **x-type:** company
- **Ownership:** Private (acquired by The Jordan Company, June 2021, $1.3B)

## Tags
 - Logistics, Freight, Trucking, Supply Chain, Third Party Logistics, Freight Brokerage, LTL, Truckload, Intermodal, EDI, Transportation Management, B2B

## Timestamps
- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

Echo exposes its EchoSync integration platform as a small family of REST APIs, gated behind OAuth 2.0 and provisioned to existing shipper / carrier / TMS partners by Echo's sales team (info@echo.com). The reference is hosted on SwaggerHub and is auth-walled; only the catalog is publicly visible at the documentation portal.

### EchoSync Authorizer API
OAuth 2.0 authorization endpoint that issues bearer tokens consumed by the EchoSync Customer API and Carrier API.

- **Human URL:** https://www.echo.com/technology/integrations/echosync/documentation/

### EchoSync Customer API
Shipper-facing REST API providing rapid access to competitive truckload quotes and rates 24/7/365, load creation, tracking, and document retrieval.

- **Human URL:** https://www.echo.com/technology/integrations/echosync/documentation/

### EchoSync Carrier API
Carrier-facing REST API enabling carriers to view available truck loads in real time, place offers, and book loads using Echo's Book It Now feature.

- **Human URL:** https://www.echo.com/technology/integrations/echosync/documentation/

### EchoSync Partner-Connect API
TMS partner integration API providing seamless load creation (Truckload, LTL, and Partial), LTL freight rating, real-time tracking, and document retrieval.

- **Human URL:** https://www.echo.com/technology/integrations/echosync/documentation/

### Echo EDI Integration
System-to-system EDI integration alongside the REST APIs via the EchoSync platform.

- **Human URL:** https://www.echo.com/technology/integrations/echosync/

## Common Properties
- [Website](https://www.echo.com/)
- [Portal](https://www.echo.com/technology/integrations/echosync/)
- [Documentation](https://www.echo.com/technology/integrations/echosync/documentation/)
- [APIReference (SwaggerHub)](https://app.swaggerhub.com/organizations/EchoGlobalLogistics)
- [Blog](https://www.echo.com/resources/blog/)
- [RSS](https://www.echo.com/feed/)
- [Press Releases](https://www.echo.com/company/about-us/press-releases/)
- [Case Studies](https://www.echo.com/resources/case-studies/)
- [White Papers](https://www.echo.com/resources/white-papers/)
- [Careers](https://www.echo.com/company/careers/open-positions/)
- [GitHub Organization](https://github.com/EchoGlobalLogistics)
- [LinkedIn](https://www.linkedin.com/company/echo-global-logistics)
- [Plans](plans/echo-global-logistics-plans-pricing.yml) - partner-provisioned, no public list pricing
- [RateLimits](rate-limits/echo-global-logistics-rate-limits.yml) - placeholder, not publicly documented
- [FinOps](finops/echo-global-logistics-finops.yml) - FOCUS-aligned, invoice-driven

## Notable Observations
- API surface is real (Authorizer, Customer, Carrier, Partner-Connect) but the OpenAPI / Swagger definitions are gated behind a SwaggerHub login; no public OpenAPI artifacts to redistribute.
- Public `EchoGlobalLogistics` GitHub org exists but only contains legacy 2013-2014 repos (a Python SOAP client fork "suds", an MVP JS template) - no published SDKs or sample clients.
- No public status page (`status.echo.com` is unreachable).
- RSS feed is wired up at `https://www.echo.com/feed/` but is currently empty of item entries.
- Pricing for both the platform and the transportation services is contract-negotiated; not self-serve.

## Maintainers
**FN:** Kin Lane

**Email:** kin@apievangelist.com
