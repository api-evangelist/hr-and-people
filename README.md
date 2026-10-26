# HR & People (hr-and-people)

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
