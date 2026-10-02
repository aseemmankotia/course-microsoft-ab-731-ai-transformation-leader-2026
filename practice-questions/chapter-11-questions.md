## Chapter 11: Process Redesign, Adoption Metrics, and Scaling from Pilot to Enterprise — Practice Questions

**Q1.** A Copilot pilot in the accounts payable team shows 92% of licensed users logging in weekly, but average invoice processing time has not changed since before the pilot. What is the MOST likely explanation, and what should the team do next?

A) Adoption is the same as impact, so the pilot is successful and ready to scale
B) Users are opening Copilot but not using it at the steps that actually remove manual work — redesign the workflow around specific high-friction steps and re-measure cycle time
C) License utilization is too low, so more licenses should be purchased before scaling
D) The pilot should be scaled immediately because high usage always predicts future cost savings

<details>
<summary>Answer</summary>

**Correct: B**

High active usage (an adoption metric) without cycle-time change (an impact metric) is the classic sign that people are using the tool superficially rather than at the process steps where it removes work. The fix is to re-map the process and redesign around the specific bottleneck steps, then re-pilot.

**Why the others are wrong:**
- Adoption and impact are distinct metric categories — high adoption does not imply impact, which is the core trap this scenario tests
- Utilization is already high (92%); the problem is where in the process it's being used, not how many licenses exist
- Scaling before impact is demonstrated is a common scaling failure mode, not a success criterion

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A team is about to launch a 6-week Copilot pilot for customer support ticket resolution. Before the pilot starts, which action is MOST critical to enable a valid before/after comparison later?

A) Record current average ticket resolution time, ticket volume per agent, and quality/CSAT scores as a baseline
B) Send a survey asking agents how helpful they expect Copilot to be
C) Purchase enough licenses for the entire support organization in case the pilot succeeds
D) Draft the executive summary slide deck in advance

<details>
<summary>Answer</summary>

**Correct: A**

Baselines must capture the same impact metrics (cycle time, volume, quality) that will be measured post-pilot, and must be recorded before the pilot begins — without this, any improvement claim after the pilot is unverifiable.

**Why the others are wrong:**
- Expectation surveys are qualitative sentiment, not a quantitative baseline for cycle-time/impact comparison
- Over-provisioning licenses before proving impact is a resourcing decision unrelated to establishing a measurable baseline
- Drafting reporting materials early does not create the data needed to prove impact

</details>

---

**Q3.** An executive sponsor asks for a mid-pilot update on a Copilot rollout. Which single reporting approach BEST satisfies executive-sponsor expectations for this stage?

A) A comparison of adoption metrics against impact metrics relative to the pre-pilot baseline, with a clear next-step recommendation
B) A full technical log of every prompt submitted by pilot users
C) A list of every feature Copilot supports, regardless of pilot relevance
D) A qualitative summary of positive comments from pilot participants only

<details>
<summary>Answer</summary>

**Correct: A**

Executive reporting should tie adoption and impact metrics back to the baseline and end with a clear, decision-oriented recommendation (continue, redesign, or scale) — this is what sponsors need to make a go/no-go call.

**Why the others are wrong:**
- Raw prompt logs are operational detail, not executive-level insight
- A feature list has no connection to measured business outcomes
- Selective positive-only feedback is not a credible measurement and omits impact data entirely

</details>

---

**Q4.** Which process-mapping technique is recommended before redesigning a workflow around a Copilot or agent?

A) Automate every step of the process regardless of complexity or judgment required
B) Skip mapping and let end users decide informally which steps to use Copilot for
C) Break the process into discrete steps and classify each as 'augment' (agent assists a human decision), 'remove' (agent fully replaces the step), or 'unchanged' (requires human judgment/exception handling)
D) Map only the steps that are already the most automated to minimize redesign effort

<details>
<summary>Answer</summary>

**Correct: C**

The tested technique is to decompose the process into steps and explicitly classify each as augment, remove, or unchanged — this classification is what drives which parts of the workflow get redesigned around the AI capability.

**Why the others are wrong:**
- Blanket automation ignores steps requiring judgment or exception handling, which is a design flaw the exam flags
- Ad hoc, ungoverned adoption produces inconsistent usage and unmeasurable impact
- Focusing only on already-automated steps yields the least redesign value, not the most

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q5.** A team wants to measure whether a Copilot deployment is reducing the actual cost of a business process, not just whether people are using it. Which category of metric should they prioritize for this specific goal?

A) Adoption metrics such as daily active users
B) License utilization rate
C) Impact metrics such as cycle-time reduction and cost savings
D) Number of prompts submitted per user per day

<details>
<summary>Answer</summary>

**Correct: C**

Cost reduction is an outcome/business-value measure, which falls under impact metrics — adoption metrics (usage, licenses, prompt counts) only measure engagement, not business outcome.

**Why the others are wrong:**
- Active user counts show engagement, not whether cost was actually reduced
- License utilization measures how many seats are used, not financial outcome
- Prompt volume is an engagement/usage signal, not a cost or outcome measure

</details>

---

**Q6.** In the pilot-to-enterprise iteration loop, what is the correct order of stages?

A) Pilot → gather feedback → redesign process → re-pilot to validate → scale
B) Scale enterprise-wide → pilot → gather feedback → redesign
C) Redesign process → scale enterprise-wide → pilot → gather feedback
D) Gather feedback → scale enterprise-wide → pilot → redesign

<details>
<summary>Answer</summary>

**Correct: A**

The iteration loop runs pilot, then feedback collection, then process redesign based on that feedback, then a re-pilot to validate the redesign actually improved metrics, and only then a decision to scale.

**Why the others are wrong:**
- Scaling before piloting skips validation entirely and is a scaling failure mode
- Redesigning and scaling before piloting means changes were never tested against real data
- Scaling before feedback is incorporated risks propagating an unvalidated process enterprise-wide

</details>

---

**Q7.** A pilot met its cycle-time and cost-savings targets, and leadership approves an enterprise rollout. Three months after rollout, usage collapses because business units report they don't know who to contact when the agent produces an incorrect output, and no one reinforces the new workflow in team meetings. Which scaling failure mode does this best describe?

A) Under-resourced support and lack of reinforcement after scaling
B) Insufficient baseline data collected before the pilot
C) Choosing the wrong impact metric during the pilot
D) Mapping the wrong process for the initial pilot

<details>
<summary>Answer</summary>

**Correct: A**

Lack of a clear support path for errors and no ongoing reinforcement (e.g., manager check-ins, workflow reminders) are the two named common scaling failure modes, distinct from problems in the pilot's design or measurement phase.

**Why the others are wrong:**
- Baseline problems would have surfaced during the pilot itself, not three months after a successful scale
- The pilot already succeeded on its impact metrics, so metric selection wasn't the issue
- The pilot's process mapping was validated by pilot success; the failure occurred after scaling

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** Which statement BEST distinguishes adoption metrics from impact metrics?

A) Adoption metrics and impact metrics measure the same thing but at different points in time
B) Adoption metrics are only used pre-pilot, and impact metrics are only used post-scale
C) Adoption metrics measure whether people are using the tool (e.g., active users, license utilization); impact metrics measure whether the business process actually improved (e.g., cycle time, cost, quality)
D) Impact metrics measure usage frequency, while adoption metrics measure business outcomes

<details>
<summary>Answer</summary>

**Correct: C**

This is the core definitional distinction tested: adoption = engagement/usage of the tool itself; impact = measurable change in the business process outcome. A pilot can show one without the other.

**Why the others are wrong:**
- They measure fundamentally different things (usage vs. outcome), not the same thing at different times
- Both metric types should be tracked throughout the pilot and after scaling, not confined to one phase
- This reverses the actual definitions of the two metric categories

</details>

---

