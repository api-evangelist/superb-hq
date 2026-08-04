# Superb (superb-hq)

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

Superb is a Denmark-based all-in-one Guest Experience Management (GXM) platform for restaurants, cafés and bars, bringing reservations, point of sale, payments, gift cards, online takeaway, guest CRM and marketing together in a single system.

**Access model — important:** Superb does **not** publish a self-serve, documented public developer API. Guest bookings are taken through a hosted reservation widget (`etch.superbexperience.com`), third-party systems connect through Superb's catalog of pre-built connectors, and any programmatic reservation / booking / guest / CRM access is **partner-gated** and arranged directly with Superb via the partner portal (`partner.superbexperience.com`). No `docs.superbexperience.com` or `api.superbexperience.com` developer reference was found.

The APIs listed below are **logical capability groupings modeled** from Superb's public product and help-center material. They are marked `endpointsModeled` because Superb does not publish endpoint-level REST documentation — no specific paths, base URL, or auth scheme have been fabricated.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/superb-hq/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/superb-hq/refs/heads/main/apis.yml)

## Tags

- Restaurants
- Reservations
- Hospitality
- Guest Experience
- GXM
- Point of Sale
- CRM
- Payments

## Timestamps

- **Created:** 2026-07-05
- **Modified:** 2026-07-05

## APIs (modeled capabilities)

### Superb Reservations API

Logical capability for creating and managing restaurant reservations — availability, floor and table assignment, booking creation and status changes. Surfaced to guests through a hosted booking widget rather than a documented public REST API. `endpointsModeled: true`.

- **Human URL:** [https://helpcenter.superbexperience.com/en/category/reservations-10nttcr/](https://helpcenter.superbexperience.com/en/category/reservations-10nttcr/)




## Common Properties

- [Website](https://www.superbexperience.com/)
- [LinkedIn](https://www.linkedin.com/company/superbexperience)
- [Documentation (Help Center)](https://helpcenter.superbexperience.com/en/)
- [Partners](https://partner.superbexperience.com/)
- [Integrations](https://www.superbexperience.com/platform/integrations)
- [Booking Widget](https://etch.superbexperience.com/reserve/experience)
- [Plans](plans/superb-hq-plans-pricing.yml)

## Pricing

Superb sells per-business SaaS on a payments transaction-fee model:

- **Go** — €0/month, 1.29% per transaction, free card terminal (shops, bars, takeaway; no reservation system).
- **Plus** — custom monthly (on-site calculator), 0.99% per transaction; adds the **reservation system**, mobile POS, online gift cards, online takeaway and email marketing (restaurants, fine dining, cafés).
- **Enterprise** — custom, for businesses processing over €500,000 annually.

There is no separately priced developer/API product.

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
