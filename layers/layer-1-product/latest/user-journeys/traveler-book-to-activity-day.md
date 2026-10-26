---
title: "User Journey: Traveler — Book to Activity Day"
layer: product
owner: "Martina Lanzi"
status: needs_review
last_updated: 2026-10-26
relates_to:
  - layers/layer-1-product/latest/Templates/product-brief.md
  - layers/layer-1-product/latest/Templates/user-personas.md
sources:
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-0-business/raw-inputs/Whiteboard Image Information/01-whiteboard-day-of-tour.png
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-1-product/raw-inputs/03-operations-follow-up.md
---

# User Journey: Traveler — Book to Activity Day

How a traveler goes from choosing an activity to completing it and leaving feedback. The steps follow the PRD v0.9 traveler journey. The feature column uses the candidate feature areas from the [Product Brief](../Templates/product-brief.md), and no feature specs exist yet. The whiteboard day-of flow (Booking → Meeting point → Check-in → Tour → Review) supports the same sequence, but its notes are prompts for discussion, not decisions.

---

## Journey Overview

A traveler, the Group Booker persona, is planning time in Lisbon or Barcelona and wants to book an activity for themselves and their group. The trigger is the trip itself, or a recommendation. They start with a destination and dates, usually on a phone, with no account and no app. The journey ends after the activity, when they receive a follow-up and can leave feedback.

---

## Journey Map

| Step | User Action | System Response | Feature | Pain Points / Notes |
| --- | --- | --- | --- | --- |
| 1 | Browses and compares activities by destination, date, interests, duration, language, price and accessibility | Shows matching activities with clear availability | Browse and activity details | |
| 2 | Reviews key conditions | Shows inclusions, restrictions, meeting point, cancellation terms and an expected total price close to the final price | Browse and activity details | Cancellation terms differ by activity |
| 3 | Enters booking details for the group and authorizes payment, as a guest | Asks only for necessary details; authorizes payment | Guest checkout and booking access | No account required |
| 4 | Waits for confirmation | Synchronized availability: confirms immediately. Manual inventory: the traveler is informed while the operator decides | Availability and booking | ⚠️ Only 38% of catalog activities can confirm immediately; operator acceptance can take up to 12 hours. Approach and wording are open, and the Executive Lead wants to see options |
| 5 | Receives status and voucher | Shows booking status, voucher and instructions; itinerary available on another device and shareable with the group | Confirmation and voucher | The voucher identifies the reservation, not each traveler. Recovery and sharing mechanism not chosen |
| 6 | Prepares for the day | Shows preparation and meeting-point details: current photo and clear address; critical information works on a weak connection | Day-of traveler experience | Offline data set and refresh not defined |
| 7 | Gets to the meeting point | Shows meeting-point instructions and any updates | Day-of traveler experience | Today travelers miss updated messages and wait in the wrong place |
| 8 | Arrives and checks in | Guide records attendance | Guide experience | Some operators check the reservation, others individual attendance; one scan does not cover a whole group |
| 9 | Completes the activity | — | — | |
| 10 | Receives follow-up and leaves feedback | Sends follow-up and invites a review | ⚠️ Not yet a feature area | |

---

## Alternative Paths

**Operator declines the request.** The traveler has paid (authorized) but the operator declines. They need a clear message and a resolution, and the AI assistant may recommend alternatives. Moving them to another paid booking needs approval from Operations or the operator. The customer message and the plan for declined requests are not yet agreed.

**Plans change on the day.** Weather, a guide running late, a blocked route or a cancellation changes the plan. The traveler should hear about it in time, through a channel they actually see, and get a recommended alternative where relevant. Guides want to know about recommendations before travelers get instructions that change the plan.

**Group arrives separately.** One person booked for several travelers who arrive at different times, or some never arrive. What each group member receives and how the guide handles partial arrivals are not yet defined.

**Booked on a laptop, used on a phone.** The traveler books on a laptop and opens the itinerary on a phone on the day, with no account. Secure recovery is required, and its mechanism is not chosen.

**Payment failure, rescheduling, no-show, refund.** These are named exceptions. Which get product support and which stay as temporary manual processes is not agreed.

---

## Entry and Exit Points

Travelers arrive from Harbor & Pine's own channels, staff or partners. Hotel partners are a possible future entry point; whether any hotel element belongs in the pilot is open. Success means the traveler booked with a clear status, arrived at the right place at the right time, completed the activity and was kept informed of any change. Failure means they abandon while waiting for confirmation, go to an outdated meeting point, or contact support because they are unsure what is happening.

---

## Open Questions

| Question | Context | Owner | Status |
| --- | --- | --- | --- |
| What does the traveler see between payment authorization and operator acceptance, and after a decline? | Executive Lead wants no visible uncertainty after payment | Executive Lead, Operations, Product Designer | Open |
| How does each traveler in a group get their own information? | Voucher represents the reservation | Product Designer, Operations | Open |
| Which day-of details work offline for travelers, and how are they refreshed? | Guide set defined; traveler set not | Tech Lead | Open |
| Is review and feedback part of the pilot? | Final step of the journey; no feature area yet | Product Manager | Open |
