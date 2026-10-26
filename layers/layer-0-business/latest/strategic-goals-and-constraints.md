---
title: "Strategic Goals and Constraints"
layer: business
owner: "Martina Lanzi"
status: needs_review
last_updated: 2026-10-26
relates_to:
  - layers/layer-0-business/latest/business-overview.md
  - layers/layer-0-business/latest/stakeholder-map.md
sources:
  - layers/layer-0-business/raw-inputs/pre-kickoff-harbor-and-pine.md
  - layers/layer-0-business/raw-inputs/00-harbor-and-pine-prd-v0.9.pdf
  - layers/layer-0-business/raw-inputs/Meetings/02-kickoff-transcript.md
  - layers/layer-0-business/raw-inputs/Meetings/04-guide-interview-notes.md
  - layers/layer-1-product/raw-inputs/03-operations-follow-up.md
---

# Strategic Goals and Constraints

What Harbor & Pine is trying to achieve, why this engagement exists, and what limits it. Every statement below comes from the client side (Executive Lead, Operations), Sales, or the team's own drafts. None of it has been formally agreed with the client yet; unresolved points are listed under Open Questions.

---

## Strategic Goals

- **Accompany the traveler end to end.** The Executive Lead wants "someone planning a trip to feel that Harbor & Pine is helping them all the way through. Discovery, booking, the actual day, everything." The goal is explicitly "bigger than a nicer website."
- **Increase completed bookings.** The Executive Lead wants booking to feel immediate ("Choose an activity, pay, get confirmation") because "we lose people when they have to wait." There is no measured abandonment figure; the evidence is what the team hears.
- **Make the day of the activity reliable.** Operations says most of its time goes to the day of the activity — old meeting points, late guides, weather, and travelers who cannot open a message — not to discovery.
- **Reduce avoidable support questions and manual work.** A new front end must not create more messages for Operations. The pilot should not increase manual communication, and every exception needs an owner and a resolution path.
- **Prepare for growth without building the whole vision at once.** Future cities and a branded hotel channel are part of the long-term vision. The hotel opportunity stays visible but must not delay the first, traveler-facing launch.

**Priority.** The goals are not ranked. The Executive Lead stresses bookings ("I still need more people to book"); Operations stresses the day of the activity. The Executive Lead's position is "We need both sides to work."

**Connection to this engagement.** Phase 1 (Strategy and Solution Design) turns these goals into a prioritized scope, the main journeys, high-fidelity designs and a handoff for development, supported by technical feasibility input.

---

## Engagement Drivers

Harbor & Pine is an established tours business that sells through a public website, staff and partner channels, and runs operations on spreadsheets, email, messaging and separate support and payment tools. There is no shared product view across travelers, guides and Operations, and the business wants a more scalable customer experience built on a new platform from scratch. Day-of failures are the most concrete symptom: tours moved for weather while a group still went to the original meeting point, guides running late, and updated messages that travelers never saw. Urgency comes from the Executive Lead, who has an eight-week date in mind and would like bookings, payments, vouchers, day-of support, something for guides and a first AI experience running in Lisbon and Barcelona by then — an expectation that has not been agreed (see Constraints). Hotel partners asking for a branded version add commercial pressure. Before kickoff, Sales relayed the client line "We should be able to confirm straight away," without clarity on whether it covers every activity; Operations later narrowed it to activities with connected availability. The cost of doing nothing has not been stated or quantified.

---

## Known Risks

These risks come from the PRD v0.9 draft and the pre-kickoff notes and are not yet reviewed with the client:

- Availability that appears confirmed before the operator accepts.
- Automation that adds manual work instead of removing it.
- Low guide adoption.
- Incorrect assistant suggestions.
- Different operator policies.
- Unreliable connectivity on the day of the activity.
- Pilot scope that exceeds the available phase.
- Unclear current systems, inventory access and client availability.

---

## Constraints

| Type | Description | Rigidity |
| --- | --- | --- |
| Budget | Phase 1 is 550 hours in total across a Product Manager, Product Designer and Tech Lead, covering discovery, ideation, scope definition and high-fidelity design with technical feasibility input. The hours are not yet allocated by role. | Hard |
| Commercial scope | Development, implementation and production QA are outside Phase 1 and follow as a separate phase. | Hard |
| Timeline | The Executive Lead refers to an eight-week pilot. Whether it means a prototype, a test or a live launch is undefined. The Tech Lead cannot confirm a live launch in that window because systems have not been assessed or implementation estimated; no implementation scope or launch date has been agreed. ⚠️ Unresolved. | Soft |
| Organizational | Operator agreements stay in force. Cancellation rules differ by activity, so a single platform cancellation policy cannot be assumed. | Hard |
| Organizational | Changes to a paid booking require approval from Operations or the operator. The AI assistant may recommend alternatives but must not change a paid booking on its own. | Hard |
| Organizational | The pilot must not increase manual communication. Each exception needs an owner and a resolution path; the acceptable amount of manual work and temporary workarounds are not agreed. | Hard |
| Organizational | Access to guides, operators and client stakeholders has to be arranged; client availability is unclear. | Soft |
| Technical | Only 38% of activities in the Lisbon and Barcelona catalog have synchronized availability (a share of activities, not of bookings or revenue). The rest is handled through spreadsheets, email or messaging, and some operators take up to 12 hours to accept a request. Private tours can also depend on guide, language and price validation. | Hard |
| Technical | Payment authorization does not mean the operator has accepted the booking. | Hard |
| Technical | "From scratch" applies to the new platform and the current website. It does not remove existing operator policies, operator systems or the tools Operations relies on during a pilot. | Hard |
| Technical | No required app download. Critical information must work on a weak connection; the exact offline data set and refresh behavior are undefined. | Hard |
| Technical | No current-system audit has been done. Which systems hold customer records and call recordings is unknown. | Soft |
| Regulatory | Traveler data is shared only as needed for activity delivery. This is a PRD-proposed rule, not yet confirmed by the client. Legal and privacy review is a dependency; its approver is not assigned. | Soft |
| Regulatory | Main flows should meet WCAG 2.2 AA. This is a team proposal, not yet confirmed by the client, and its approver is not assigned. | Soft |
| Scope | The planned pilot (per the PRD draft and the pilot brief) is traveler-facing, in Lisbon and Barcelona, in English and Spanish. Portuguese, French and Italian are revisited together with the hotel channel. ⚠️ Operations expects to revisit some draft assumptions after checking Lisbon and Barcelona. | Soft |
| Process | The current website is not shown to the team and is not a design reference. Process examples and anonymized booking messages are available instead. | Hard |

---

## Open Questions

| Question | Context | Owner | Status |
| --- | --- | --- | --- |
| What must exist at week eight: a prototype, a test with real travelers, or a live launch? | Executive Lead's expectation vs a design-only Phase 1 | Executive Lead, Product | Open |
| What implementation effort follows Phase 1, and who carries it? | Development is a separate phase | Executive Lead, Product | Open |
| How should bookings growth and day-of reliability be prioritized against each other? | Goals are unranked | Executive Lead, Operations | Open |
| What does doing nothing cost the business? | No figure stated | Executive Lead | Open |
| Who approves accessibility and privacy requirements? | Not assigned | Executive Lead | Open |
| What amount of manual work and which temporary workarounds are acceptable in the pilot? | Raised by Operations | Operations, Product | Open |
| Does Phase 1 include a prototype, and how much technical detail goes into the handoff? | "To align at kickoff"; the kickoff recording ended before the remaining agenda items | Product Director | Open |
