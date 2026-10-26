---
title: "Product Brief"
layer: product
owner: "Martina Lanzi"
status: needs_review
last_updated: 2026-10-26
relates_to:
  - layers/layer-0-business/latest/strategic-goals-and-constraints.md
  - layers/layer-0-business/latest/business-overview.md
  - layers/layer-0-business/latest/stakeholder-map.md
sources:
  - layers/layer-0-business/raw-inputs/pre-kickoff-harbor-and-pine.md
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-0-business/raw-inputs/Whiteboard Image Information/01-whiteboard-day-of-tour.png
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-1-product/raw-inputs/03-operations-follow-up.md
---

# Product Brief

What we are building for Harbor & Pine, for whom, and why. The scope below is a candidate direction for the pilot, not an approved backlog; open points are listed at the end.

---

## Problem Space

Travelers need to know what they are booking, whether it is confirmed, where to meet and what to do when plans change. Only 38% of catalog activities have synchronized availability and can confirm immediately; for the rest the operator must accept the request, which can take up to 12 hours, even after payment has been authorized. The share of bookings affected is unknown. The Executive Lead believes travelers abandon when they have to wait, though there is no measured figure. Operations reports that most of its effort goes to the day of the activity: outdated meeting points, guides running late, weather changes and messages travelers never see. In one case three tours were moved for weather and a group still went to the meeting point in their original email.

Guides receive group lists from several operators through different tools, sometimes in conflicting versions or while already on the way, on older phones with poor reception. Operations absorbs these exceptions by hand, and escalation is "not always the same person." There is no shared view across travelers, guides and Operations. The cost is lost bookings, avoidable support contacts and manual work; none of it has been quantified yet.

---

## Target Users

The **traveler** is the primary user and the audience of the first launch. Travelers usually book on a phone, and one person may book for a group. **Guides** and **Operations** are secondary users who keep the day of the activity running: guides need current group information with little extra administration, and Operations needs to see problems early enough to act and to approve changes. **Operators** are external users who control availability, prices and policies and accept or decline requests. **Hotel partners** are a future audience for a branded channel. See [User Personas](user-personas.md).

---

## Product Vision

Harbor & Pine helps a traveler all the way through a trip — discovering an activity, booking it with an honest, quick confirmation, and arriving at the right place on the day even when plans change — from a link that opens on a phone without an app download. Behind that experience, guides get a current, offline-ready group list and Operations sees exceptions early, with clear owners and approvals. An AI assistant recommends alternatives when something changes, but people stay in control of paid bookings. Unlike today's mix of a website, spreadsheets, email and messaging, travelers, guides and Operations share one current picture of each booking.

---

## Scope

Phase 1 produces the prioritized scope, the main journeys, high-fidelity designs and a development handoff; implementation is a separate phase. The Executive Lead would like bookings, payments, vouchers, day-of support, something for guides and a first AI experience running in Lisbon and Barcelona by the eight-week date. The Tech Lead cannot confirm a live launch in that window, and no implementation scope or launch date is agreed. The candidate pilot scope, based on the PRD v0.9 draft, covers:

- **Browse and activity details:** compare activities by destination, date, interests, duration, language, price and accessibility. Show inclusions, restrictions, meeting point and cancellation terms.
- **Availability and booking:** clear availability and an expected total price close to the final price. Immediate confirmation for synchronized availability. For manual inventory, the traveler is informed while the operator decides, including when a request is declined. ⚠️ The approach and wording are open; the Executive Lead wants to see options.
- **Guest checkout and booking access:** no account required. The itinerary is recoverable on another device and shareable with a group.
- **Confirmation and voucher:** booking status, voucher and instructions.
- **Day-of traveler experience:** meeting-point instructions, voucher, support and updates without a required app download. Critical information works on a weak connection.
- **Guide experience:** schedule and group information available offline, attendance and no-shows, delay reporting and help requests. Works on older phones with little typing.
- **Operations experience:** booking status, exception review, contacting the right people and approving changes. Keeps existing tools where that is the simplest pilot approach.
- **AI assistant:** recommends alternatives before and during an activity. Paid-booking changes go to human approval.

The planned pilot, per the PRD draft and the pilot brief, covers Lisbon and Barcelona in English and Spanish. ⚠️ Operations expects to revisit some draft assumptions after checking both cities.

The proposed pilot readiness conditions are not yet agreed:
- A traveler can complete the main booking journey.
- A guide can manage the group.
- Operations can handle expected exceptions.

Acceptable manual effort, supported exceptions, temporary workarounds and launch criteria still need agreement.

**Out of scope or deferred:**
- **Implementation and production QA:** a separate phase after Phase 1.
- **Required app download:** travelers and guides use a link.
- **Mandatory account:** checkout stays short.
- **AI changing paid bookings on its own:** Operations or the operator must approve.
- **A single platform cancellation policy:** operator agreements differ by activity.
- **Replacing operator tools, agreements or integrations:** "from scratch" covers the new platform, not the operators' world.
- **Hotel branded channel:** not in the first, traveler-facing launch, and it must not delay the pilot. ⚠️ Whether any hotel element belongs in the pilot, or a concept for partners in Phase 1, is open.
- **Portuguese, French and Italian:** revisited together with the hotel channel.
- **Live map:** not a requirement; a current photo and clear address may serve meeting points better.
- **AI that listens to calls and supports staff:** floated by the Executive Lead; not scoped.
- **Cities beyond Lisbon and Barcelona:** future growth.

---

## Key Assumptions

- **Faster, clearer confirmation increases completed bookings.** Untested: there is no abandonment figure, only what the team hears.
- **Travelers will accept a clear "waiting for operator" state after paying.** Untested, and in tension with the Executive Lead's wish that nothing feels uncertain after payment. The customer-facing wording is undecided.
- **Guides will adopt a new tool if it opens fast, needs little typing and works offline.** Based on two remote interviews. One guide would keep messaging until the tool is trusted.
- **Critical day-of information can work offline from a link, without an app.** Not technically validated. Whether "offline" means after the link has been opened once is undefined.
- **The product can work with existing operator tools and agreements.** Operations requires this. Feasibility is not yet assessed, since there is no system audit.
- **The 38% synchronized share reflects what travelers will experience.** Unverified. It is a share of activities, not of bookings or revenue.

---

## Relationship to Business Goals

The product serves the strategic goals in [Strategic Goals and Constraints](../../layer-0-business/latest/strategic-goals-and-constraints.md):
- **Completed bookings:** a quick, honest booking flow and guest checkout serve this goal.
- **Day-of reliability:** the traveler day-of experience, the offline guide list and Operations visibility serve this goal.
- **Less manual work and fewer avoidable support questions:** exception owners, approvals and timely updates serve this goal, so the new front end does not add messages for Operations.
- **Growth:** preparing for new cities and hotel partners without building them into the pilot.

Success for the product means more travelers completing bookings, fewer support contacts per booking, less manual handling time and guides actually using the tool. These measures are tracked in [Success Metrics](success-metrics.md).

---

## Open Questions

| Question | Context | Owner | Status |
| --- | --- | --- | --- |
| When can a manual booking be described as confirmed, and what does the traveler see while it waits or if it is declined? | Executive Lead wants no visible uncertainty; Operations needs an agreed message | Executive Lead, Operations, Product Designer | Open |
| Which details must be available offline for travelers, how are they refreshed, and how is a saved list marked outdated? | Guide data set defined; traveler set not | Tech Lead, Operations | Open |
| How can a guest recover and share a booking securely, and what does each member of a group receive? | Voucher identifies the reservation, not each traveler | Product Designer, Tech Lead | Open |
| Which AI behavior comes first: recommendations, staff support during calls, or help during the trip? | "Recommendations are an obvious starting point" | Executive Lead | Open |
| Which exceptions get product support, and which use a temporary manual process? | Acceptable manual work not agreed | Operations, Product Manager | Open |
| Does a hotel concept for partners belong in Phase 1? | Sales wants something to show soon | Sales, Executive Lead | Open |
| Is the "pilot brief" PRD v0.9? | Referenced at kickoff | Product Director | Open |
