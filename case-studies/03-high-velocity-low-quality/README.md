# High Velocity but Declining Quality

**Primary Skill:** Quality + Metrics

> **Portfolio case study:** This is a realistic simulation intended to demonstrate Scrum Master problem-solving. It should not be presented as a claim of specific client/project experience.

---

## 1. Scenario:

The Scrum Team's velocity has increased across several Sprints. However, production defects, rework, technical debt, and customer complaints are also increasing.

Stakeholders are initially celebrating the higher velocity, while Developers are experiencing increasing pressure to maintain the same level of output.

The Scrum Master notices that the team may be optimizing for **output rather than product quality and value**.

---

## 2. Business / Delivery Impact:

Increasing velocity creates the perception of improved productivity, but declining quality creates hidden delivery costs.

Potential impacts include:

- More escaped defects
- Increased rework
- Growing technical debt
- Customer dissatisfaction
- Reduced confidence in releases
- Developer frustration
- More time spent fixing previously completed work
- Pressure to maintain an artificially high velocity

The team may gradually start optimizing for **story count instead of delivering a usable, valuable Increment**.

---

## 3. What I Would Observe:

Before proposing a solution, I would inspect the system and look for patterns such as:

- Rising escaped defects
- Increasing rework
- Defect severity trends
- Growing technical debt
- Stories considered Done before full validation
- Testing being pushed toward the end of the Sprint
- Increasing pressure to maintain velocity
- Velocity being used as a productivity target
- Quality-related work not being visible during Sprint Planning
- Definition of Done not adequately reflecting the required quality standards

The objective is to understand the **system behind the numbers**, rather than reacting to a single metric.

---

## 4. Root Cause Analysis:

The first question I would ask is:

> **Are we actually delivering more valuable Done work, or are we simply completing more work items?**

Possible contributing factors include:

### Metric-driven behavior

Velocity may have unintentionally become a performance target.

When a metric becomes a target, the team can start optimizing the metric rather than the outcome it was intended to represent.

### Weak Definition of Done

If testing, acceptance criteria, security checks, documentation, or other quality activities are not consistently part of the Definition of Done, work may be counted as complete before it is truly ready.

### Quality work becoming invisible

Technical debt, refactoring, automation, defect prevention, and other quality activities may not receive appropriate attention during planning.

### Late quality feedback

If validation happens primarily at the end of the Sprint, defects may be discovered too late, increasing rework.

The goal is not to find someone to blame, but to identify **where the system is encouraging undesirable behavior**.

---

## 5. Scrum Master's Approach:

I would approach this through **inspection, transparency, and adaptation** rather than immediately introducing more process.

### Step 1 — Inspect the Definition of Done

Facilitate a conversation with the Scrum Team to determine whether the Definition of Done represents the quality required for a usable Increment.

Questions could include:

- Does "Done" include adequate testing?
- Are acceptance criteria fully validated?
- Are automation and regression expectations clear?
- Are security or performance checks relevant to the product?
- Can a story be considered Done while known quality issues remain?

### Step 2 — Make quality visible

Bring quality signals into Sprint Reviews and Retrospectives.

Instead of looking at velocity alone, inspect a balanced set of signals such as:

- Escaped defects
- Rework
- Defect severity
- Technical debt
- Sprint Goal achievement
- Customer feedback
- Release quality

### Step 3 — Coach stakeholders on velocity

Explain that velocity is useful primarily as a **planning and forecasting aid**.

It should not become:

- An individual performance metric
- A team productivity score
- A target to increase every Sprint
- A basis for comparing teams

### Step 4 — Make quality work visible

Help the team make technical debt, defect prevention, refactoring, automation, and other quality-related work transparent during Product Backlog refinement and Sprint Planning.

### Step 5 — Inspect the working system

If quality problems continue, facilitate deeper conversations around:

- Testing practices
- Code review
- Automation
- Pairing or collaboration
- Early feedback
- Technical debt
- Development practices

The Scrum Master should help the team identify and address systemic issues rather than prescribing a solution on behalf of the Developers.

---

## 6. Metrics to Inspect:

I would avoid relying on velocity alone.

A balanced view could include:

| Signal | What it can help us understand |
|---|---|
| Velocity trend | Planning/forecasting pattern |
| Escaped defects | Quality after release |
| Rework rate | Effort spent correcting previous work |
| Defect severity | Business/customer impact |
| Technical debt | Future delivery risk |
| Sprint Goal achievement | Outcome focus |
| Customer feedback | Product impact |
| Cycle/lead time | Flow and delivery efficiency |

> **Important:** These metrics should support inspection and improvement, not individual performance evaluation.

---

## 7. Improvement Experiment:

Rather than introducing a large process change immediately, the team would agree on a small, measurable experiment.

### Problem

Velocity is increasing while escaped defects and rework are also increasing.

### Hypothesis

If quality expectations are made explicit through a stronger Definition of Done and quality checks are performed earlier, escaped defects and rework should decrease.

### Experiment

For the next **2–3 Sprints**, the team could:

- Review and strengthen the Definition of Done
- Make quality-related work visible during planning
- Perform validation earlier in the workflow
- Track escaped defects and rework
- Discuss quality trends during Retrospectives

### Measure

Compare the relevant quality signals before and after the experiment.

```text
Problem
   ↓
Hypothesis
   ↓
Experiment
   ↓
Measure
   ↓
Inspect
   ↓
Adapt

## 8. Expected Outcome:

The desired outcome is not simply a higher or lower velocity.

The goal is to increase confidence that the team is delivering a **valuable, usable, and high-quality Increment**.

Expected improvements may include:

- Fewer escaped defects
- Reduced rework
- Better quality transparency
- More sustainable delivery
- Improved stakeholder understanding
- Better visibility of technical debt
- Stronger Definition of Done
- More realistic forecasting

> **Note:** Velocity may stabilize or even decrease initially. This is not necessarily a negative outcome if the team is delivering more genuinely Done and valuable work.

---

## 9. Scrum Master Learning:

One of the biggest lessons from this scenario is:

> **High velocity does not automatically mean high performance.**

A metric becomes dangerous when it becomes a target.

The Scrum Master's role is not to maximize velocity.

The Scrum Master helps create an environment where the Scrum Team can:

- Inspect outcomes
- Identify impediments
- Improve quality
- Make problems transparent
- Continuously adapt

The focus should remain on **sustainable delivery of a valuable, usable Increment**.

---

## 10. Interview Answer:

> **"If velocity rises while escaped defects and rework are also increasing, I would treat that as a warning signal rather than automatically celebrating the higher velocity. I would inspect the Definition of Done and the quality signals with the team, understand where quality is being compromised, and facilitate a small improvement experiment. I would also coach stakeholders that velocity is a planning aid, not a productivity or performance target. The objective would be sustainable delivery of a valuable, usable Increment."**

---

## 11. Visual:

```mermaid
flowchart LR
A[Velocity ↑] --> B[Inspect Quality Signals]
B --> C{Quality Declining?}
C -- Yes --> D[Inspect Definition of Done]
D --> E[Identify Root Causes]
E --> F[Improvement Experiment]
F --> G[Measure Outcomes]
G --> H[Inspect & Adapt]
C -- No --> I[Continue Monitoring]

## 12. Portfolio Takeaway:

> **The Scrum Master creates the conditions for the team to solve the problem; the Scrum Master does not become the team's problem solver.**

### Key Takeaway:

**Velocity is a useful planning signal, but sustainable quality and valuable outcomes matter more than maximizing the number.**