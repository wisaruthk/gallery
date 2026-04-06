---
name: Engineering Manager OS
description: Rapid-reference playbook for engineering management — team building, 1:1s, performance, hiring, incident response, and scaling.
metadata:
  homepage: https://github.com/wisaruthk/gallery/tree/main/skills/engineering-manager
---

# Engineering Manager Operating System

Quick-reference system for high-performing engineering managers. Use these frameworks daily.

## Phase 1: Team Health (Monthly)

Score 1-5: Delivery pace, Quality, Collaboration, Morale, Learning, Autonomy, Psychological safety, On-call health.
- ≤2 = Crisis (address this week)
- 3 = Improvement plan (2 weeks)
- <3.5 average = Block new work

Ideal team mix: Tech lead, 2-3 senior ICs, 2-3 mid-level, 0-2 juniors, 1 domain expert. Never >60% at same level.



## Phase 2: 1:1 System

**Cadence:** Direct reports weekly (30 min), skip-levels monthly (30 min), your manager weekly (30 min), cross-functional peers bi-weekly (25 min).

**Template:** Their agenda first → Check energy (1-10) → Current work + blockers → Career growth → Action items.

**Question bank:** "What's on your mind?" | "Where do you want to be in 2 years?" | "Who do you learn from most?" | "What's one thing I could do differently?"

**Flight risk signals:** LinkedIn update, declining engagement, stopped volunteering, hidden interviews, disengaged in meetings, complaining about org, mental checkout. 3+ signals = retention conversation within week.

## Phase 3: Performance Management

**Rating:** Score on two axes: Delivery Impact (1-4) × Behaviors (1-4). Calibration matrix drives outcomes.

**Feedback framework:** "In [situation], when you [behavior], impact was [concrete]. I'd like [change] because [why]."

**PIP:** 30-90 days, specific expectations, weekly check-ins, HR review. 70% end in termination—use as documentation tool.

**Promotion case:** Evidence over 6+ months: technical complexity, scope ownership, influence, business impact. Include peer feedback. Timing matters for retention.



## Phase 4: Hiring

Pipeline: Role → Job description → Screen → Tech screen → Take-home/coding → Onsite → Debrief → Offer → Close (target: <21 days).

Interview scorecard: Score each dimension 1-4 (force decision, skip 3). Any strong_no = veto. Decide same day.

Offer call: Express excitement (2 min) → Details (3 min) → Philosophy (3 min) → Listen (2 min) → Resolve concerns → 3-5 day deadline → Close.

## Phase 5: Technical Leadership

Code review SLA: <4 hrs first review, <2 hrs follow-up, max 400 lines. Review: correctness, edge cases, security, naming. Tone: ask questions, praise good work, offer to pair if >5 comments.

Tech debt priority matrix: Impact (1-5) × Cost of not fixing (1-5). 20-25 = emergency sprint. 12-19 = 2 sprints. 6-11 = quarterly budget (15-20%). 1-5 = backlog.

ADR template: Context → Options (pros/cons/effort/risk) → Decision + WHY → Consequences → Review date.

## Phase 6-8: Sprint, Incidents, Scaling

**Sprint metrics:** Completion rate 80-100%, carry-over 0-1, PR cycle <48h, bugs <10%, deploys daily/weekly, sprint goal binary.

**Incident framework:** Severity (SEV1-4) → Timeline → Root cause (systems, not people) → Action items with owners/dates.

**On-call health:** Pages <5/wk, off-hours <2/wk, acknowledge <5 min, false positives <20%, team size 4+, max 2 consecutive weeks.

**Org splitting:** Team >8? Split. Different domains? Split. Standup >15 min? Split. Define boundaries, split backlog, split on-call, name teams, designate tech leads, give 3 months.

## Phase 9-10: Communication & Rituals

**Weekly status:** Sprint goal → Shipped → In progress → Risks → Metrics → Next priorities.

**Managing up:** Solutions with problems. Flag risks early. Quantify impact. Clear asks with deadlines. Proactive updates. Disagree privately.

**Daily ritual (15 min):** Scan Slack for blockers → Standup (listen) → Check PR queue → Give one piece of feedback.

**Weekly:** All 1:1s → Sprint metrics → Status update → Calendar audit → Skip-level or cross-functional chat.

**Monthly:** Team health radar → Career development 1:1s → Tech debt review → On-call health → Update team topology.

**Quarterly:** Performance calibration → Team goals → Architecture review → Headcount planning → Ask team for feedback on YOU.



## Difficult Situations (Quick Reference)

**Architecture disagreement:** Design docs → Define criteria → 60 min discussion → Tech lead decides → ADR → Monitor commitment.

**IC wants to manage:** Explore motivation → Test with projects → Be honest on tradeoffs → Offer Staff/IC path → 3-month check-in.

**Low-performing team:** Week 1-2 listen → Identify systemic issue → Month 2 one win → Month 3 address performance. Never blame predecessor.

**Layoffs:** Pre-plan coverage → Honest comms → 48h 1:1s → Audit workload → Self-care.

**Best engineer leaving:** Same-day conversation (not counteroffer) → Understand why → Celebrate them → Knowledge transfer → Team comms.

## Effectiveness Rubric (0-100)

Team health (20%) + Delivery (20%) + People development (20%) + Technical stewardship (15%) + Hiring (10%) + Communication (10%) + Self-improvement (5%).

- 90-100: Exceptional
- 75-89: Strong
- 60-74: Developing
- 40-59: Struggling
- <40: Intervention needed

## Quick Commands

- "Prepare 1:1 with [name]" → Agenda from recent context
- "Write performance review for [name]" → Calibrate using framework
- "Create job description for [role]" → Use template
- "Run team health check" → Score radar dimensions
- "Draft ADR for [decision]" → Context → Options → Decision → Consequences
- "Incident post-mortem for [incident]" → Template with timeline + RCA + action items
- "Flight risk assessment" → Check signals per team member
- "Interview scorecard for [candidate]" → Score dimensions 1-4, recommendation
