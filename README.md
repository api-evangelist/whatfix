# Whatfix

Whatfix is a digital adoption platform providing in-app contextual guidance, SaaS management, workflow automation, and product analytics to help organizations accelerate software adoption, improve employee onboarding, and optimize digital transformation. Its platform combines guided walkthroughs, self-help content, AI-powered authoring agents, task lists, surveys, and usage analytics for web, desktop, mobile, and VDI environments.

**Website:** https://whatfix.com

## APIs

### Whatfix API

The Whatfix REST API enables programmatic access to end-user management, content management, flow analytics, segmentation, and report downloads. The API is stateless, uses JSON output, and authenticates via the `x-whatfix-integration-key` header.

- **Developer Portal:** https://developer.whatfix.com
- **Developer Guide:** https://support.whatfix.com/docs/developer-guide
- **Authentication:** https://support.whatfix.com/docs/generatingtheapitoken
- **Base URL:** https://whatfix.com/api/v1

### SDKs

- **Android SDK:** https://github.com/whatfix/whatfix-android — DAP solution for native Android apps
- **iOS SDK:** https://github.com/whatfix/Whatfix-iOS — DAP solution for native iOS apps

## OpenAPI Specifications

| Spec | Description |
|---|---|
| [Whatfix API](openapi/whatfix-openapi.yml) | REST API covering end users, content, analytics, segments, and reports |

## Examples

| Example | Description |
|---|---|
| [List End Users](examples/whatfix-list-end-users-example.json) | List all tracked end users with pagination |
| [Get Flow Analytics](examples/whatfix-get-flow-analytics-example.json) | Get flow views and completion rates for a date range |
| [Upsert End User](examples/whatfix-upsert-end-user-example.json) | Create or update an end user with segmentation attributes |
| [List Content](examples/whatfix-list-content-example.json) | List all published flows and content items |

## Spectral Rules

- [whatfix-rules.yml](rules/whatfix-rules.yml) — Spectral ruleset enforcing Whatfix API conventions

## Naftiko Capabilities

### Workflow Capabilities

| Capability | Description |
|---|---|
| [digital-adoption.yaml](capabilities/digital-adoption.yaml) | Unified digital adoption monitoring — end users, content, analytics, segmentation (9 tools) |

### Shared API Definitions

| File | API |
|---|---|
| [shared/whatfix-api.yaml](capabilities/shared/whatfix-api.yaml) | Whatfix REST API v1 |

## JSON Schemas

| Schema | Description |
|---|---|
| [Whatfix End User](json-schema/whatfix-end-user-schema.json) | End user for analytics and segmentation |
| [Whatfix Content](json-schema/whatfix-content-schema.json) | Content items including flows, tooltips, task lists |

## JSON Structures

| Structure | Description |
|---|---|
| [Whatfix End User](json-structure/whatfix-end-user-structure.json) | End user structure |
| [Whatfix Content](json-structure/whatfix-content-structure.json) | Content item structure |

## JSON-LD Context

- [whatfix-context.jsonld](json-ld/whatfix-context.jsonld) — Linked data context for digital adoption platform vocabulary

## Vocabulary

- [whatfix-vocabulary.yml](vocabulary/whatfix-vocabulary.yml) — Domain vocabulary for digital adoption, content types, segmentation, and analytics

## Common Resources

| Type | URL |
|---|---|
| Website | https://whatfix.com |
| Developer Portal | https://developer.whatfix.com |
| Documentation | https://support.whatfix.com |
| GitHub Organization | https://github.com/whatfix |
| Blog | https://whatfix.com/blog/ |
| Pricing | https://whatfix.com/pricing/ |
| Integrations | https://whatfix.com/integrations/ |

**Maintainer:** Kin Lane (kin@apievangelist.com)
