# HR & People (hr-and-people)

API and integration profile for the **HR and people-operations** landscape — an API Evangelist topic index covering the major HRIS, unified-HRIS, payroll, applicant-tracking, performance / engagement, and people-data API providers.

The focus of this repo is the **portable shape of an Employee record** as it moves across these systems: a JSON Schema for the entity, a JSON-LD context aligning the vocabulary with schema.org/Person, and a shared people-operations vocabulary keyed to the catalog of providers below.

## Provider Catalog

### HRIS

| Provider | Developer docs |
|---|---|
| Workday | https://community.workday.com/api |
| BambooHR | https://documentation.bamboohr.com/docs |
| Rippling | https://developer.rippling.com |
| Gusto | https://docs.gusto.com |
| Justworks | https://www.justworks.com/developers |
| Paylocity | https://www.paylocity.com/our-products/integrations |
| ADP | https://developers.adp.com |
| UKG | https://developer.ukg.com |
| Sage People | https://developer.sage.com/hr |
| Personio | https://developer.personio.de |
| HiBob | https://apidocs.hibob.com |
| Namely | https://developers.namely.com |

### Unified HRIS APIs

| Provider | Developer docs |
|---|---|
| Merge HRIS | https://docs.merge.dev/hris/overview |
| Finch | https://developer.tryfinch.com |
| Kombo | https://docs.kombo.dev |

### Applicant Tracking / Talent Acquisition

| Provider | Developer docs |
|---|---|
| Greenhouse | https://developers.greenhouse.io |
| Lever | https://hire.lever.co/developer |
| Workable | https://workable.readme.io |
| SmartRecruiters | https://developers.smartrecruiters.com |
| Ashby | https://developers.ashbyhq.com |

### Performance & Engagement

| Provider | Developer docs |
|---|---|
| Lattice | https://lattice.com/api |
| Culture Amp | https://www.cultureamp.com/integrations |
| 15Five | https://help.15five.com/hc/en-us/categories/360002374972 |

### People Data & Compensation

| Provider | Developer docs |
|---|---|
| LinkedIn Talent Solutions | https://learn.microsoft.com/en-us/linkedin/talent |
| HiPeople | https://www.hipeople.io/api |
| Compa | https://www.compa.as |
| OpenComp | https://www.opencomp.com |

## Artifacts in this Repo

| Artifact | Path |
|---|---|
| Topic index | [apis.yml](apis.yml) |
| Employee JSON Schema | [json-schema/hr-and-people-employee-schema.json](json-schema/hr-and-people-employee-schema.json) |
| Employment JSON Schema | [json-schema/hr-and-people-employment-schema.json](json-schema/hr-and-people-employment-schema.json) |
| Employee JSON Structure | [json-structure/hr-and-people-employee-structure.json](json-structure/hr-and-people-employee-structure.json) |
| JSON-LD context (schema.org/Person aligned) | [json-ld/hr-and-people-context.jsonld](json-ld/hr-and-people-context.jsonld) |
| Employee example | [examples/hr-and-people-employee-example.json](examples/hr-and-people-employee-example.json) |
| Employment example | [examples/hr-and-people-employment-example.json](examples/hr-and-people-employment-example.json) |
| People-operations vocabulary | [vocabulary/hr-and-people-vocabulary.yml](vocabulary/hr-and-people-vocabulary.yml) |

## Why a Topic Repo

The HR & People landscape is unusually fragmented: a single Employee record has its system of record in an HRIS, gets re-shaped by payroll, gets enriched by an ATS at hire, and gets re-projected by performance, engagement, identity, and compensation tools. Unified-HRIS APIs (Merge, Finch, Kombo) have done a lot of work to converge on a portable shape, and this repo captures that shared shape — independent of any one vendor — so it can be used as a contract by AI capabilities, identity automations, and people-data warehouses.

## Maintainer

- Kin Lane — [API Evangelist](https://apievangelist.com) — kin@apievangelist.com
