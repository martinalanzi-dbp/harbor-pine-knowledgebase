---
title: "Domain Glossary"
layer: product
owner: "Martina Lanzi"
status: needs_review
last_updated: 2026-10-26
relates_to:
  - layers/layer-0-business/latest/business-overview.md
sources:
  - layers/layer-0-business/raw-inputs/pre-kickoff-harbor-and-pine.md
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-1-product/raw-inputs/03-operations-follow-up.md
---

# Domain Glossary

Shared vocabulary for the Harbor & Pine product. Use these terms with these meanings in every layer.

---

## Terms

### People and organizations

| Term | Definition | Context / Notes |
| --- | --- | --- |
| Traveler | The end customer who browses, books and attends an activity. | Usually on a phone. One traveler may book for a group. |
| Guide | The person who leads an activity on the day. | Often works for several operators, each sending information through different tools. |
| Operator | A third-party business that delivers activities and controls their availability, prices, policies and delivery. | Not the same as Operations. Operators accept or decline requests and approve changes to paid bookings. |
| Operations | Harbor & Pine's internal team that handles assignments, changes, incidents, cancellations, refunds and escalations. | Not the same as Operator. |
| Hotel partner | A hotel that recommends Harbor & Pine activities to its guests. | A possible future branded channel. Not in the first, traveler-facing launch; its pilot role is open. |
| Executive Lead | The client's point of contact and apparent sponsor. | Name not yet shared. |

### Booking and inventory

| Term | Definition | Context / Notes |
| --- | --- | --- |
| Activity / Tour | A bookable experience delivered by an operator. | Used interchangeably in client conversations. |
| Synchronized availability | Activities whose availability is connected to Harbor & Pine, so a booking can be confirmed immediately. | Also called connected inventory. 38% of activities in the Lisbon and Barcelona catalog. |
| Manual inventory | Activities whose availability is handled through spreadsheets, email or messaging. | The operator must accept each request; some take up to 12 hours. |
| Booking request | A traveler's booking for manual inventory that is waiting for operator acceptance. | Can be accepted or declined. |
| Payment authorization | A hold on the traveler's payment, taken before the operator accepts. | Does **not** mean the booking is accepted. |
| Operator acceptance | The operator's agreement to deliver a requested booking. | Required for manual inventory. Private tours can also depend on guide, language and price validation. |
| Declined request | A booking request the operator refuses. | Needs an agreed customer message and handling plan. |
| Confirmed booking | A booking the business can promise to deliver. | ⚠️ When a manual booking can be called "confirmed" is not yet defined. |
| Internal status / customer-facing status | The detailed status Operations tracks vs the status the traveler sees. | Internal statuses may be more detailed. The mapping and the wording shown to travelers are not yet defined. |
| Reservation / Booking | A single purchase that may cover several travelers. | |
| Group booking | One reservation covering several travelers. | Travelers in a group may arrive separately. |
| Voucher | The proof of reservation the traveler receives after booking. | Identifies the reservation, **not** each traveler. |
| Guest checkout | Booking without creating an account. | No account is required to book. |
| Itinerary | The traveler's view of their booked activities and instructions. | Must be reachable on another device (for example, booked on a laptop, viewed on a phone). The recovery mechanism is not yet chosen. |
| Cancellation terms | The rules for cancelling a specific activity. | Set by each operator's agreement; differ by activity. There is no single platform policy. |
| Paid-booking change | Any change to a booking that has already been paid: moving, rescheduling, swapping. | Requires approval by Operations or the operator. The AI assistant may not make it on its own. |

### Day of the activity

| Term | Definition | Context / Notes |
| --- | --- | --- |
| Day of the activity (day-of) | Everything that happens on the activity date: getting to the meeting point, check-in, the tour itself. | Where Operations spends most of its time. |
| Meeting point | Where the group meets the guide. | Frequent source of confusion. A current photo and a clear address might help more than a live map in some locations. |
| Group list | The list of travelers expected on an activity, sent to the guide. | Guides receive it through different tools; versions can conflict. |
| Outdated list | A saved group list that has been superseded by a later change. | How an outdated list is marked is not yet defined. |
| Check-in / attendance | Recording which travelers have arrived. | Some operators check the reservation; others need individual attendance. One scan does not resolve attendance for a whole group. |
| Split arrival | Travelers from one group booking arriving at different times. | Guides handle it differently today. |
| No-show | A booked traveler who does not arrive. | Guides want a quick way to record it. |
| Exception | Any deviation from the planned booking or activity, such as manual confirmation, payment failure, weather, guide delay, weak connectivity, split arrival, cancellation or refund. | Each exception needs an owner and a resolution path. |
| Offline / weak connection | Critical information remaining available without a fresh connection. | For guides: group list, meeting point, language and emergency contact. The traveler data set and refresh behavior are not yet defined. |

### Product and engagement

| Term | Definition | Context / Notes |
| --- | --- | --- |
| AI assistant | The assistant that helps travelers before and during an activity. | May recommend alternatives; may not change a paid booking on its own. Its first behavior is not chosen. |
| Pilot | The first, traveler-facing launch. | Planned for Lisbon and Barcelona in English and Spanish, per the PRD draft and the pilot brief. ⚠️ Scope, timing and relationship to the eight-week date are not agreed. |
| Eight-week date | The Executive Lead's target for seeing a first experience running. | Not agreed as a launch date. |
| Phase 1 (Strategy and Solution Design) | The signed 550-hour design phase. | Not the same as the pilot. Development follows separately. |
| Pilot brief | The brief that defines pilot languages (English and Spanish). | ⚠️ Likely PRD v0.9; not confirmed. |
| Hotel channel | A possible branded experience for hotel partners. | Must not delay the pilot; whether any part belongs in it is open. |

---

## Acronyms

| Acronym | Expansion | Usage Context |
| --- | --- | --- |
| AE | Account Executive | Sales owner of the account |
| AI | Artificial intelligence | The traveler assistant |
| KPI | Key performance indicator | Success metrics |
| MVP | Minimum viable product | First-version scope |
| PRD | Product requirements document | PRD v0.9 (draft for alignment, May 11, 2026) |
| QR | Quick Response (code) | Possible check-in method; not validated |
| SOW | Statement of work | Phase 1 commercial scope |
| WCAG 2.2 AA | Web Content Accessibility Guidelines 2.2, level AA | Proposed accessibility target for main flows |
