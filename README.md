# Playroll (playroll)

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

Playroll is a global HR platform providing Employer of Record (EOR), contractor management, and global payroll across 180+ countries. It runs local payroll, statutory benefits, and compliance for distributed teams, and offers a partner/enterprise integration surface - native HRIS connectors (HiBob, BambooHR), an "Open API" for bi-directional HR data sync, and custom/embedded integration builds. The developer API is partner- and enterprise-gated; sandbox access and documentation are provided to integration partners rather than published on a public developer portal.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/playroll/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/playroll/refs/heads/main/apis.yml)

## API Availability

Playroll has a genuine integration/developer surface but **no public, self-serve API**. There is no public developer portal, no published OpenAPI/API reference, no public webhook documentation, and no public Playroll GitHub organization. Access to the "Open API," sandbox, and documentation is granted to approved integration partners through Playroll's partner program and solutions-engineering team. The API entries below are **modeled** from Playroll's public product and partner materials, not confirmed from an API reference. See [review.yml](review.yml) for the full availability assessment.

## Tags

- HR
- Employer of Record
- EOR
- Global Payroll
- Contractor Management
- Global Employment
- HRIS
- Compliance

## Timestamps

- **Created:** 2026-07-01
- **Modified:** 2026-07-01

## APIs

### Playroll EOR API

Partner/enterprise integration surface for Playroll's Employer of Record product - hire, onboard, and manage full-time employees in 180+ countries through Playroll's owned entities without your business setting up local entities. Exposed to integration partners via Playroll's Open API and custom builds; endpoints are modeled, not confirmed from a public reference.

- **Human URL:** [https://www.playroll.com/employer-of-record](https://www.playroll.com/employer-of-record)

#### Tags

- Employer of Record
- EOR
- Global Employment

#### Properties

- [Documentation](https://www.playroll.com/employer-of-record)
- [Integrations](https://playroll.com/integrations)

### Playroll Contractor Management API

Onboard, contract, and pay international contractors compliantly in 180+ regions. Modeled as part of Playroll's partner integration surface for contractor lifecycle and payments; not a publicly documented endpoint set.

- **Human URL:** [https://www.playroll.com/pricing/employer-of-record](https://www.playroll.com/pricing/employer-of-record)

#### Tags

- Contractor Management
- Contractors
- Compliance

#### Properties

- [Documentation](https://www.playroll.com/)
- [Integrations](https://playroll.com/integrations)

### Playroll Global Payroll API

Run and consolidate global payroll across entities and countries, with statutory calculations and local pay runs. Surfaced to partners for payroll data sync and reporting via Playroll's Open API; endpoints modeled from product capabilities rather than a published API reference.

- **Human URL:** [https://www.playroll.com/workforce-management-software](https://www.playroll.com/workforce-management-software)

#### Tags

- Global Payroll
- Payroll
- Payments

#### Properties

- [Documentation](https://www.playroll.com/workforce-management-software)
- [Integrations](https://playroll.com/integrations)

### Playroll Workforce Data API

Bi-directional workforce/employee data sync surface behind Playroll's Open API and native HRIS connectors (HiBob, BambooHR), keeping employee records, org data, and documents aligned across an integrated HR/finance stack. Modeled from Playroll's integrations product; not a public developer reference.

- **Human URL:** [https://playroll.com/integrations](https://playroll.com/integrations)

#### Tags

- HRIS
- Workforce
- Employee Data

#### Properties

- [Integrations](https://playroll.com/integrations)
- [Documentation](https://www.playroll.com/partners)

### Playroll Partner Integration API

The gated developer entry point for ATS, HRIS, accounting, and workforce platforms that want to embed Playroll (integrate, co-sell, reseller/white-label). Partners receive sandbox access and documentation from Playroll's solutions-engineering team; no self-serve public API keys or open docs portal are published.

- **Human URL:** [https://www.playroll.com/partners](https://www.playroll.com/partners)

#### Tags

- Partners
- Embedded
- White Label

#### Properties

- [Documentation](https://www.playroll.com/partners)
- [White Label](https://www.playroll.com/white-label-hr-software)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/playroll)
- [Website](https://www.playroll.com)
- [Documentation](https://playroll.com/integrations)
- [Partners](https://www.playroll.com/partners)
- [Plans](plans/playroll-plans-pricing.yml)
- [Rate Limits](rate-limits/playroll-rate-limits.yml)
- [Fin Ops](finops/playroll-finops.yml)

## Collections

- [Postman Collection](collections/playroll.postman_collection.json) — modeled scaffold, partner-completable
- [Open Collection](collections/playroll.opencollection.json) — modeled scaffold, partner-completable

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
