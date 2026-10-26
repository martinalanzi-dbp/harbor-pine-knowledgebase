---
title: "User Journey: Guide — Run an Activity Day"
layer: product
owner: "Martina Lanzi"
status: needs_review
last_updated: 2026-10-26
relates_to:
  - layers/layer-1-product/latest/Templates/product-brief.md
  - layers/layer-1-product/latest/Templates/user-personas.md
sources:
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Whiteboard Image Information/01-whiteboard-day-of-tour.png
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-1-product/raw-inputs/03-operations-follow-up.md
---

# User Journey: Guide — Run an Activity Day

How a guide prepares for and runs an activity, from checking the group list to closing out attendance. It is based on two remote guide interviews; no tour has been observed.

---

## Journey Overview

A guide, the Multi-Operator Guide persona, is assigned to lead an activity for one of several operators. The trigger is an upcoming activity. They expect a group list the night before and work on an older phone with limited battery and patchy reception. The goal is to meet the right group at the right place, run the activity, and record who came, with as little typing as possible.

---

## Journey Map

| Step | User Action | System Response | Feature | Pain Points / Notes |
| --- | --- | --- | --- | --- |
| 1 | Checks the schedule and group list the night before | Shows the current group list: names, group size, language and relevant needs | Guide experience | Today lists come from different operators and tools |
| 2 | Checks again before leaving | Shows the latest list and flags anything changed since the last view | Guide experience | ⚠️ How an outdated saved list is marked is not defined. Today the last list can arrive while the guide is on the way |
| 3 | Travels to the meeting point with poor reception | Group list, meeting point, language and emergency contact available offline | Guide experience | Must work on older phones without draining battery |
| 4 | Meets the group | Travelers have meeting-point photo and address | Day-of traveler experience | Today travelers send screenshots to check they are in the right place |
| 5 | Marks arrivals and no-shows | Records attendance quickly | Guide experience | Some operators check the reservation, others individual attendance; one scan does not cover a whole group |
| 6 | Runs the activity, adapting the route if needed | — | — | Wants advance notice before any recommendation changes travelers' plans |
| 7 | Reports a delay or requests help if something goes wrong | Sends a quick report to Operations with minimal typing | Guide experience, Operations experience | Emergency handling not explored |

---

## Alternative Paths

**Conflicting lists.** The guide receives a list of 8, then a list of 10, and calls Operations to check whether the two extra people are confirmed. The product should make the current list unambiguous; today guides tell versions apart by message time and sender.

**Running late.** The guide is delayed on the way to the meeting point. They need to report it quickly, and travelers need to be told. What travelers receive and who acts is not defined.

**Split arrival.** Part of a group arrives first and the rest arrive later or not at all. Today guides track this from memory. A quick way to record no-shows is wanted, and check-in rules per operator have not been collected.

**Plan changes from weather or a recommendation.** The tour or route changes because of weather, a blocked street or an assistant recommendation. Guides want to know before travelers receive instructions and do not want the tour changed without notice.

**Messaging in parallel.** Until the tool earns trust, guides keep using messaging. During the pilot, the product has to coexist with messaging.

---

## Entry and Exit Points

Guides receive assignments from operators or Operations. Success means they met the right group at the right place, knew about every change in advance, and recorded attendance and incidents without long forms. Failure means working from an outdated list, travelers waiting in the wrong place, or falling back to calls and messages because the tool could not be trusted or would not load.

---

## Open Questions

| Question | Context | Owner | Status |
| --- | --- | --- | --- |
| How does a saved list get marked as outdated after a change? | Raised by Operations | Tech Lead, Operations | Open |
| How do operators check in groups, and what happens with partial arrivals? | Varies by operator; not collected | Operations | Open |
| How should emergencies be handled from the guide's side? | Not explored in interviews | Operations | Open |
| Which traveler data may guides see? | Guide A: names, group size, language, relevant needs; no access policy defined | Operations, Tech Lead | Open |
| How often do conflicting lists and wrong meeting points actually happen? | Frequency not measured | Operations | Open |
