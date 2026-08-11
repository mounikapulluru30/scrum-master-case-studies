# Recovering a Team That Keeps Missing Sprint Goals

**Primary Skills:** Facilitation • Root Cause Analysis • Coaching • Metrics • Continuous Improvement

> ## 📌 Portfolio Simulation
>
> **Scenario-based case study — not a claim of specific client, employer, or production experience.**
>
> This simulation demonstrates how I would approach a Scrum Team that has missed its Sprint Goal for three consecutive Sprints. The metrics and outcomes presented are illustrative and are intended to demonstrate my Scrum Master problem-solving approach.

---

## 1. Scenario

A Scrum Team has missed its Sprint Goal for three consecutive Sprints, even though estimates appear reasonably consistent.

The team is completing a significant amount of work, but the **Sprint Goal is repeatedly not achieved**.

This creates concerns around:

- Predictability
- Stakeholder confidence
- Sprint Planning effectiveness
- Team focus
- Quality
- Sustainable delivery

The Scrum Master's objective is **not simply to increase velocity**.

The objective is to understand why the team is repeatedly failing to achieve valuable Sprint outcomes and help the team improve its ability to deliver toward a meaningful Sprint Goal.

---

## 2. Business / Delivery Impact

Repeatedly missing Sprint Goals can lead to:

- Reduced stakeholder confidence
- Increasing carryover between Sprints
- More pressure during Sprint Planning
- Teams optimizing for individual task completion rather than the Sprint Goal
- Increased context switching
- Late discovery of dependencies
- Testing and integration being pushed toward the end of the Sprint
- Reduced ability to forecast near-term outcomes

The Scrum Master should therefore focus on **systemic causes rather than blaming individual team members**.

---

## 3. What I Would Inspect

Before proposing solutions, I would inspect the team's recent Sprint data and facilitate discussion around the following areas.

### Delivery Signals

- Sprint Goal achievement
- Planned vs. completed work
- Carryover work
- Unplanned work
- Blocked time
- Dependency-related delays
- Work added after Sprint Planning

### Product Backlog Signals

- Story size
- Story splitting
- Acceptance criteria
- Refinement quality
- Dependency visibility
- Technical uncertainty
- Product Owner availability

### Team / Flow Signals

- Work in Progress
- Handoffs
- Waiting time
- Testing bottlenecks
- Code review delays
- Integration delays
- Collaboration patterns

### Quality Signals

- Defects found during the Sprint
- Regression issues
- Rework
- Escaped defects
- Definition of Done adherence

> **Important:** I would avoid using velocity alone as evidence of team performance.

---

## 4. Initial Observations

For this simulation, assume the following patterns are identified:

1. Several stories are carried over between Sprints.
2. Unplanned production/support work frequently enters the Sprint.
3. Some stories are too large to complete comfortably within one Sprint.
4. Dependencies are discovered after Sprint Planning.
5. Testing activity is concentrated toward the end of the Sprint.
6. Team members sometimes optimize for completing individual tasks instead of achieving the Sprint Goal.
7. The Sprint Goal is sometimes too broad to provide a clear focus.

These observations suggest that **estimation accuracy may not be the primary problem**.

---

# 5. Root Cause Analysis

I would facilitate a collaborative root-cause analysis with the Scrum Team rather than diagnosing the problem alone.

## 5.1 Example 5 Whys

### Problem

**The team repeatedly misses the Sprint Goal.**

**Why 1:**  
Why is the Sprint Goal not achieved?

→ Multiple items remain incomplete at the end of the Sprint.

**Why 2:**  
Why do multiple items remain incomplete?

→ Stories are larger than expected, dependencies emerge, and unplanned work interrupts the Sprint.

**Why 3:**  
Why are these issues discovered during the Sprint?

→ Refinement and dependency identification are not consistently uncovering risks before Sprint Planning.

**Why 4:**  
Why isn't refinement identifying these risks early?

→ Some stories lack sufficient acceptance criteria, technical understanding, or cross-functional discussion.

**Why 5:**  
Why does this continue?

→ The team has not established a consistent feedback loop for learning from carryover, blocked work, and Sprint Goal failures.

### Root Cause Hypothesis

The primary issue is not necessarily inaccurate estimation.

The stronger hypothesis is:

> **Insufficient focus on Sprint Goal clarity, work slicing, dependency visibility, refinement quality, and managing unplanned work.**

---

# 6. Scrum Master's Assessment

My assessment would be:

> **The team does not primarily need better estimation. It needs better inspection and adaptation around how work enters, flows through, and exits the Sprint.**

I would avoid immediately:

- Increasing estimates
- Reducing velocity targets
- Blaming developers or testers
- Asking the team to "work harder"
- Comparing individual performance
- Using velocity as a productivity target

Instead, I would help the team identify the **systemic constraints affecting Sprint Goal achievement**.

---

# 7. Proposed Scrum Master Approach

## Step 1 — Reconnect the Team With the Sprint Goal

During Sprint Planning, I would facilitate discussion around:

> **"What valuable outcome are we trying to achieve this Sprint?"**

Rather than treating the Sprint Backlog as a list of unrelated tasks, I would encourage the team to understand how the selected work contributes to the Sprint Goal.

### Desired behavior

Instead of:

> "I completed my assigned tickets."

Move toward:

> "What does the team need to do to achieve the Sprint Goal?"

---

## Step 2 — Improve Story Slicing

I would coach the team and Product Owner on splitting oversized stories into smaller, valuable increments.

Possible techniques include:

- Split by workflow
- Split by business rule
- Split by user role
- Split by happy path / alternative path
- Split by data variation
- Split by CRUD operation where appropriate
- Separate technical risk from functional delivery

### Goal

Create work items that can move through:

**Development → Review → Testing → Done**

within the Sprint instead of accumulating partially completed work.

---

# 8. Step 3 — Strengthen Product Backlog Refinement

I would facilitate refinement around:

- Clear acceptance criteria
- Dependencies
- Technical risks
- External dependencies
- Testability
- Story size
- Business value
- Definition of Ready, where the team finds it useful

I would encourage the team to ask:

> **"What could prevent this item from reaching Done within the Sprint?"**

This shifts refinement from simply discussing requirements to **identifying delivery risks early**.

---

# 9. Step 4 — Make Dependencies Visible

I would introduce a simple dependency discussion during refinement and Sprint Planning.

For example:

| Dependency | Owner | Risk | Mitigation |
|---|---|---|---|
| API availability | Backend Team | High | Confirm before Sprint |
| Test environment | QA/DevOps | Medium | Validate environment |
| External approval | Business Stakeholder | Medium | Identify approver early |
| Third-party service | External Team | High | Track dependency |

The goal is not to create excessive documentation.

The goal is to make important dependencies **visible before they become blockers**.

---

# 10. Step 5 — Make Unplanned Work Visible

If support or production work regularly enters the Sprint, I would not simply ignore it.

I would help the team visualize:

**Planned Work + Unplanned Work = Actual Capacity Consumption**

For example:

```text
Sprint Capacity
│
├── Planned Product Work       75%
│
├── Support / Unplanned Work   15%
│
└── Other Interruptions        10%
```

The team and Product Owner can then discuss whether the Sprint commitment reflects reality.

If recurring support work is significant, I would facilitate discussion around an appropriate team-level strategy rather than allowing hidden work to distort Sprint commitments.
## 11. Step 6 — Improve Cross-Functional Collaboration

If development and QA are working sequentially, I would encourage earlier collaboration.

Instead of:

Development → Development → Development → QA → Bug Fix → Retest

encourage:

Story A → Develop → Review → Test → Done
Story B → Develop → Review → Test → Done
Story C → Develop → Review → Test → Done

This supports earlier feedback and reduces the risk of discovering multiple issues immediately before the Sprint ends.

## 12. Step 7 — Facilitate a Focused Retrospective

Rather than asking:

"What went well?"

and

"What didn't go well?"

I would focus the retrospective on the recurring Sprint Goal problem.

Example retrospective questions
What prevented us from achieving the Sprint Goal?
Which issues repeated across all three Sprints?
Which problem had the highest impact?
What was within our control?
What should we stop doing?
What should we start doing?
What is one experiment we can run in the next Sprint?

The objective is to leave the retrospective with one or two actionable experiments, rather than a long list of actions.

## 13. Illustrative Metrics

Note: The following numbers are illustrative and created specifically for this portfolio simulation. They do not represent actual project data.

Before Improvement
| Metric | Sprint 1 | Sprint 2 | Sprint 3 |
|---|---:|---:|---:|
| Planned Story Points | 32 | 30 | 31 |
| Completed Story Points | 22 | 21 | 23 |
| Carryover | 10 | 9 | 8 |
| Unplanned Work | 5 | 6 | 7 |
| Sprint Goal | ❌ | ❌ | ❌ |

Key observation

The issue is not simply that completed points are low.

The more important signals are:

High carryover
Increasing unplanned work
Repeated Sprint Goal failure
Potentially oversized stories
Late discovery of blockers

## 14. Improvement Experiment

For the next Sprint, I would propose a focused experiment.

Experiment

Improve Sprint Goal achievement by reducing work-in-progress and making dependencies visible earlier.

Actions
Define a concise Sprint Goal.
Split oversized stories.
Review dependencies during refinement.
Make unplanned work visible.
Encourage earlier development-QA collaboration.
Track carryover and blocked time.
Discuss Sprint Goal progress during Daily Scrum.
Experiment duration

1 Sprint

The team should treat this as an experiment rather than a permanent process change.

## 15. Illustrative Expected Results

These are target outcomes for the simulation, not claims of actual project results.

| Metric | Before | Illustrative Target |
|---|---:|---:|
| Sprint Goal Achievement | 0/3 | 1/1 next Sprint |
| Carryover | 8–10 SP | ≤ 2–3 SP |
| Unplanned Work | 5–7 SP | ≤ 2–3 SP |
| Dependency Discovery | Often during Sprint | Primarily during refinement |
| Large Stories | Frequent | Reduced |
| Late Testing | Frequent | Reduced |

The goal is not to optimize every metric simultaneously.

The primary success criterion is:

The team consistently achieves a meaningful Sprint Goal with sustainable flow and quality.

## 16. Definition of Success

I would consider the intervention successful if the team demonstrates:

Outcome
Improved Sprint Goal achievement
Reduced carryover
Better visibility of unplanned work
Earlier identification of dependencies
Smaller and more manageable work items
Team Behavior
Increased collaboration
Less individual task optimization
More focus on the Sprint Goal
More ownership of improvement experiments
More constructive retrospective discussions
Quality
Earlier testing and feedback
Reduced rework
Better adherence to the Definition of Done

## 17. What I Would Avoid

As Scrum Master, I would avoid treating the situation as an individual performance problem.

I would not:

❌ Pressure developers to increase output

❌ Set velocity targets

❌ Compare individual team members

❌ Use velocity to evaluate performance

❌ Automatically reduce estimates

❌ Add more status meetings

❌ Ask the team to work overtime as the primary solution

❌ Blame QA for incomplete stories

Instead, I would facilitate the team in identifying and addressing systemic constraints.

## 18. What I Would Learn From the Experiment

After the next Sprint, I would inspect:

Did the experiment improve Sprint Goal achievement?

If yes:

→ Continue, inspect, and adapt.

If partially successful:

→ Identify which constraint remains.

If unsuccessful:

→ Revisit the root-cause hypothesis rather than immediately adding another process.

This supports the Scrum principle of:

Inspect → Adapt → Improve

## 19. Scrum Master Skills Demonstrated

This case study demonstrates the following capabilities:

| Capability | Demonstrated Through |
|---|---|
| Facilitation | Root-cause analysis and retrospective |
| Coaching | Story slicing and team behavior |
| Servant Leadership | Removing systemic impediments |
| Data-Driven Thinking | Sprint and flow metrics |
| Stakeholder Management | Transparency around delivery risks |
| Conflict Prevention | Avoiding blame-based discussions |
| Continuous Improvement | One-Sprint experiment |
| Scrum Knowledge | Sprint Goal, refinement, Daily Scrum, retrospective |
| Quality Mindset | Definition of Done and early testing |
| Systems Thinking | Looking beyond estimation |

## 20. Interview Discussion
Interview Question

"A Scrum Team has missed its Sprint Goal for three consecutive Sprints despite accurate estimation. What would you do?"

My Answer

"I would avoid assuming that estimation is the root cause. First, I would inspect the Sprint Goals, carryover, unplanned work, dependencies, blocked time, story size, refinement quality, and quality signals.

I would then facilitate a focused retrospective with the team to identify recurring systemic constraints.

Based on the findings, I might focus on improving Sprint Goal clarity, slicing oversized stories, identifying dependencies earlier, making unplanned work visible, and encouraging earlier collaboration between development and QA.

I would select one or two improvements as a short-term experiment, define measurable success criteria, and inspect the results in the next Sprint.

My goal would not be to increase velocity. My goal would be to help the team consistently achieve meaningful Sprint Goals while maintaining sustainable quality and flow."

## 21. Key Takeaway

When a team repeatedly misses Sprint Goals, don't immediately optimize estimation. Inspect the system that produces the outcome.

A Scrum Master's role is to help the team:

Make problems visible → Understand the system → Facilitate improvement → Experiment → Inspect → Adapt

📌 Portfolio Note

This case study is intentionally designed as a scenario-based simulation to demonstrate Scrum Master reasoning and problem-solving.

The scenario, metrics, improvement experiment, and expected results are illustrative and should not be interpreted as claims of specific client, employer, or production experience.
