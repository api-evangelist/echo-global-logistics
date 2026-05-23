# Echo Global Logistics (echo-global-logistics)

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
