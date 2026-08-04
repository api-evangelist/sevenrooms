# SevenRooms (sevenrooms)

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

SevenRooms is a guest experience, reservations, and retention platform for the hospitality industry, helping restaurants, hotels, nightlife, and entertainment venues manage reservations, waitlists, CRM, and marketing. Founded in 2011 and serving clients in more than 1,000 cities worldwide, the platform unifies a restaurant tech stack with 100-plus integrations across POS, payments, booking channels, delivery, and marketing tools, plus a flexible RESTful API. The API exposes reservation, guest profile, and feedback data and supports searching availability and creating bookings. Access to the partner-facing developer documentation is gated to approved venue operators and integration partners via individually provisioned accounts (as of February 26, SevenRooms moved to individually provisioned documentation accounts).

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/sevenrooms/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Restaurant, Reservations, Waitlist, CRM, Marketing, Hospitality, Guest Experience

## Timestamps

- **Created:** 2026-06-02
- **Modified:** 2026-06-03

## APIs

### SevenRooms API
The SevenRooms API is a RESTful interface for hospitality data and operations. It exposes reservations, guest profiles, and feedback scores, and supports retrieving venue info, searching shift-level availability, and creating, modifying, or cancelling reservations including party size, table assignment, booking channel, and tags. Authentication uses OAuth2 with a provisioned client_id and client_secret scoped to a venue group. Access to the documentation is gated to approved venue operators and integration partners through individually provisioned accounts.

**Human URL:** [https://api-docs.sevenrooms.com/](https://api-docs.sevenrooms.com/)

#### Tags:

 - Reservations, Availability, Guest Profiles, Feedback

#### Properties

- [Documentation](https://api-docs.sevenrooms.com/)
- [APIReference](https://api-docs.sevenrooms.com/)
- [Authentication](https://api-docs.sevenrooms.com/) — OAuth2 (client_id / client_secret)

## Common Properties

- [Website](https://sevenrooms.com/)
- [Documentation](https://api-docs.sevenrooms.com/)
- [APIReference](https://sevenrooms.com/platform/integrations-apis/)
- [SignUp](https://sevenrooms.com/lets-talk/) — Partnerships / API Access Request
- [Login](https://www.sevenrooms.com/login)
- [Support](https://api-docs.sevenrooms.com/) — API Integration Support (api-integration-support@sevenrooms.com)
- [GitHubOrganization](https://github.com/sevenrooms)
- [Pricing](https://sevenrooms.com/request-a-demo/) — Quote-Based (Request a Demo)
- [Plans](plans/sevenrooms-plans-pricing.yml)
- [RateLimits](rate-limits/sevenrooms-rate-limits.yml)
- [FinOps](finops/sevenrooms-finops.yml)
- [TermsOfService](https://sevenrooms.com/terms-of-service/)
- [PrivacyPolicy](https://sevenrooms.com/privacy-policy/)
- [Compliance](https://sevenrooms.com/dpa/) — Data Processing Addendum
- [LinkedIn](https://www.linkedin.com/company/sevenrooms)
- [X](https://x.com/sevenrooms)

## Features

| Name | Description |
|------|-------------|
| Reservations & Waitlist | Real-time availability, online and in-house bookings, and waitlist management across shifts and seating areas. |
| CRM & Guest Profiles | Automatic guest profile building that centralizes preferences, visit history, spend, and tags for personalized service. |
| Table & Floor Management | Seating optimization and floor-plan control for venue operations. |
| Email & SMS Marketing | Automated, multi-channel marketing campaigns driven by guest profile and behavioral data. |
| Loyalty & Perks | Guest retention, rewards, and perks programs. |
| Event & Private Dining Management | Booking and management of private dining and special events. |
| Reputation Management | Review monitoring and response across feedback channels. |
| Voice AI | AI-powered phone reservation automation and phone-to-booking conversion. |
| Online Ordering | Direct-to-consumer online ordering platform. |
| Reporting & Analytics | Business intelligence dashboards for venue performance. |

## Use Cases

| Name | Description |
|------|-------------|
| Unify the Restaurant Tech Stack | Consolidate reservations, CRM, marketing, and operations across 100-plus integrations into a single hospitality platform. |
| Multi-Channel Reservation Distribution | Accept and synchronize bookings across discovery and booking channels such as Google, TheFork, and TripAdvisor. |
| Programmatic Availability & Booking | Retrieve venue info, search shift-level availability, and create, modify, or cancel reservations via the RESTful API. |
| Guest Data Capture & Personalization | Build unified guest profiles from reservations, POS, payments, and WiFi capture to drive personalized marketing and service. |

## Integrations

| Name | Description |
|------|-------------|
| POS Systems | 35-plus point-of-sale integrations including Square, Toast, Lightspeed, MICROS Simphony, NCR Aloha, Revel, and SpotOn. |
| Payments | Stripe, Adyen, CyberSource, FreedomPay, and Network International. |
| Booking Channels | Google, Facebook, Instagram, TheFork, TripAdvisor, Reserveout, Chope, and OpenRice. |
| Delivery & Pickup | DoorDash Drive, Olo, Deliverect, ItsaCheckmate, Drive Yello, and Orkestro. |
| SMS & Voice | Twilio, SMSGlobal, Bookline, Slang, Amazon Alexa, and VoiceMpower. |
| Marketing & CRM | Mailchimp, Emma, and Widewail. |
| Hotel & Events | Revinate, Journey, Tripleseat, and iVvy. |

## Artifacts

Machine-readable API specifications organized by format.

### Plans

- [SevenRooms Plans & Pricing](plans/sevenrooms-plans-pricing.yml)

### Rate Limits

- [SevenRooms Rate Limits](rate-limits/sevenrooms-rate-limits.yml)

### FinOps

- [SevenRooms FinOps](finops/sevenrooms-finops.yml)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
