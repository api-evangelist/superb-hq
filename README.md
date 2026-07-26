# Superb (superb-hq)

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
