# Round 4 Reflection: Final Project Decision

**Name**: Connor Cummings
**PennKey**: connorcc
**Date**: 11/05/2025

---

## 1. What I Explored Today

*List the projects you seriously considered. Keep it brief.*

| Project Name | Source     | Key Takeaway (1 sentence)                                                                                              |
| ------------ | ---------- | ---------------------------------------------------------------------------------------------------------------------- |
| TerraTruth   | Round 3    | Claude’s feedback made it clear the scope was bloated and the plan too ambitious to execute in 5 weeks.                |
| GroupMeet    | Instructor | Straightforward, shippable concept (22/30) with a concrete recruitment path via a professor partnership.               |
| WeTrack      | R1 Drop    | Solid idea (20/30) with strong incentives, but still hampered by a smaller version of TerraTruth’s cold-start problem. |

**Resources I used**:

* [ X ] Rubric scoring (RUBRIC-PROJECT-VIABILITY.md)
* [ X ] V2 detailed analyses (reports/v2-analyses/)
* [ X ] Steelman Analysis pathways (STEELMAN-ANALYSIS.md)
* [ X ] Group discussions
* [ ] Other: [specify]

---

## 2. My Decision

**Project Name**: GroupMeet

**Decision type**:

* [ ] STAYING with Round 3 project (same approach)
* [ ] STAYING with Round 3 project (modified approach/scope)
* [ ] PIVOTING to different project
* [ X ] JOINING another team's project

**If pivoting or adopting someone's idea**:

* Original author (if applicable): Instructor
* Original round: Instructor idea

---

## 3. Why This Decision

**High-level reasoning (2–3 paragraphs):**

The V2 readout for TerraTruth (15/30) was a decisive “stop” signal. It surfaced two issues we couldn’t reasonably fix within the timeline: a sprawling tech stack (e.g., PostGIS, AI pre-filtering, and too many features) and a recruiting plan built on wishful thinking rather than secured channels. Continuing would have meant under-building a complex system while failing to get enough users to validate anything.

WeTrack scored better (20/30) and had a compelling incentive loop, but it still leaned on groups forming themselves—creating a milder version of TerraTruth’s cold-start trap. We’d risk spending the critical weeks herding participants instead of testing the product.

GroupMeet (22/30) directly addresses both risks. Technically, it’s lean: a simple intake form, a one-shot matcher, and an email nudge. On recruitment, it trades vague outreach for a single, testable wedge—course-staff distribution in a large lecture—giving us an immediate, captive audience. That lets us prove or falsify the concept in Week 1, which is exactly where we want the risk to be.

**What convinced me**:

* The TerraTruth V2 score (15/30) accurately called out non-viable scope and recruitment.
* GroupMeet has a crisp MVP we can ship fast (a one-class pilot in ~2 weeks).
* Recruitment is centered on one concrete, binary test (professor partnership), not diffuse social campaigns.

**What concerns me** (and how I’ll address it):

* **Risk 1**: No professor agrees in Week 1. → **Mitigation**: Email 3–4 large-course instructors (CIS 1200, MATH 1400, ECON 0100) on Day 1 to diversify our chances.
* **Risk 2**: Low form completion or weak matches. → **Mitigation**: Keep the form to ~3 high-signal questions and include a specific study-style preference to improve grouping.

---

## 4. What I’m Building

**One-sentence project description**:
A lightweight web app that forms study groups for large Penn courses by matching students on course, availability, and study preferences.

**MVP Scope (3–4 core features only):**

1. **Student Preference Form**: Short form with course selection, broad availability (e.g., weeknights/weekends), and one study-style preference.
2. **One-Time Matching Script**: Manual batch job that clusters submissions into groups of 4–5.
3. **Email Distribution**: Automatic introduction email to each group with member contacts.
4. **Group Quality Rating**: A single-question follow-up (1–5 stars) sent ~5 days later.

**What I’m explicitly NOT building**:

* Real-time matching or lobby UX
* In-app chat (use GroupMe/Discord)
* Complex calendar/availability UI

---

## 5. Week 1 Validation

**The specific test I’ll run Week 1**:

* **Where**: Email professors for CIS 1200 and CIS 5480 (I TA CIS 5480), and reach out to ENVS 1000 and CIS 1210 staff.
* **When**: Monday, Nov. 10 at 9:00 AM.
* **What**: A concise message pitching a 2-week pilot to help students form study groups before finals, including the live form link.
* **Success metric**: At least one professor posts/sends our link to their class, and we capture sign-ups from ≥15% of that roster.

**If Week 1 test fails, I will**:

* [x] Try different recruitment channel: bypass instructors and post directly to large unofficial course GroupMes/Slacks and r/UPenn with a strong CTA.
* [ ] Pivot to: [alternative approach]
* [ ] Use MTurk/paid participants
* [ ] Simplify the task to: []
* [ ] Other: [specify]

---

## 6. **Tentative** Team (Optional)

**Team members**:

1. Alexander Mehta (amehta26) — Engagement Lead & Backend
2. Brandon Yan (bdonyan) — Frontend / UI
3. Joshua Lee (jlee0902) — Backend / Database
4. [Name] ([PennKey]) — [Primary role] *(optional)*

**Team status**:

* [ ] Same team from Round 3
* [ X ] New team formed during Round 4
* [ ] Solo (will find teammates later)
* [ ] Joining an existing team

---

## 7. Reflection

**Most valuable part of Round 4**:
The frank V2 on TerraTruth—it forced us to drop sunk-cost thinking and confront scope + recruitment reality.

**Biggest surprise**:
How the simplest instructor ideas still enable real validation. “Working and used” beats “impressive and unvalidated.”

**One thing I’d tell future students about Round 4**:
Treat “Stop and Pivot” as a gift, not a setback—it saves you from five painful weeks and a weak outcome.

---

## Commitment

**I commit to**:

* [ X ] Building the MVP scope above (3–4 features max)
* [ X ] Running a concrete Week 1 validation test
* [ X ] Pivoting if Week 1 shows <20% success
* [ X ] Meeting with instructor if I hit major blockers

**Signature**: Connor Cummings
**Date**: 11/6/25

