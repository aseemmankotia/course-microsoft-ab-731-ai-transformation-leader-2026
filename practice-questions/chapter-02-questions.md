## Chapter 2: Identifying and Prioritizing High-Value Use Cases — Practice Questions

**Q1.** A retail company's AI council reviews a proposed use case: an internal chatbot that answers HR policy questions. Estimated business value is low (saves ~200 hours/year across the company), but feasibility is very high (structured HR docs already exist, no PII risk, off-the-shelf RAG pattern). Using a value-versus-feasibility matrix, where should this use case be placed and what should happen to it?

A) High value, high feasibility — fund it as a flagship strategic bet with dedicated budget
B) Low value, low feasibility — deprioritize and remove from the roadmap entirely
C) High value, low feasibility — send to a research track for long-term exploration
D) Low value, high feasibility — treat as a quick win, batch it with similar low-effort items and greenlight quickly without deep review

<details>
<summary>Answer</summary>

**Correct: D**

Low value + high feasibility is the classic 'quick win' quadrant: it should move fast with minimal governance overhead precisely because effort and risk are low, even though the value alone wouldn't justify a large initiative.

**Why the others are wrong:**
- Value here is explicitly low, not high, so it does not qualify as a flagship strategic bet needing dedicated budget.
- Feasibility is high, not low, so full removal ignores the fact that it is cheap to execute; the matrix logic still favors doing it.
- The scenario states feasibility is very high, not low, so it doesn't belong in a long-horizon research track.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** An insurance company's leadership team has an executive sponsor pushing hard for a claims-summarization use case with only moderate projected ROI, while a higher-ROI fraud-detection use case has no assigned business owner and lukewarm stakeholder interest. Following prioritization best practice, which action should the company take first?

A) Fund the fraud-detection use case first because ROI is the only valid prioritization criterion
B) Defer both use cases until a single unified sponsor is found for the entire AI portfolio
C) Fund the claims-summarization use case first, since strong sponsorship reduces execution risk and adoption failure, and pursue sponsorship for fraud detection in parallel
D) Run both as full-scale production deployments simultaneously to avoid delay

<details>
<summary>Answer</summary>

**Correct: C**

Sponsorship is a feasibility input, not a nice-to-have: unsponsored use cases are far more likely to stall in change management and adoption even if ROI is higher, so pairing a sponsored moderate-value case with active work to secure a sponsor for the higher-value one is the standard portfolio move.

**Why the others are wrong:**
- ROI alone ignores feasibility factors like sponsorship, data readiness, and change-management risk, which the matrix explicitly weighs.
- Waiting for a single portfolio-wide sponsor unnecessarily blocks a viable, sponsored quick win.
- Full-scale simultaneous production deployment skips piloting and contradicts using a phased, risk-managed rollout.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q3.** A company has approved 14 generative AI pilots across 6 business units, all running concurrently with a small central AI enablement team supporting all of them. Three months in, no pilot has reached a go/no-go decision, and teams report unclear ownership of evaluation criteria. What is this scenario a direct example of?

A) Portfolio balancing across functions, which is working as intended
B) Pilot paralysis, caused by running too many parallel pilots without capacity to properly evaluate and conclude them
C) A correctly prioritized quick-win portfolio
D) Data readiness risk being properly mitigated

<details>
<summary>Answer</summary>

**Correct: B**

Pilot paralysis occurs when the number of concurrent pilots exceeds the organization's capacity to staff, evaluate, and make decisions on them, resulting in stalled initiatives with no clear outcomes — exactly what's described.

**Why the others are wrong:**
- Portfolio balancing means spreading a manageable, resourced set of bets across functions, not overloading a thin central team with 14 simultaneous efforts.
- Quick wins are supposed to move fast to decision; none of these pilots has reached a decision point, so this isn't a working quick-win portfolio.
- Data readiness is a feasibility input assessed before selection, and the scenario doesn't describe data issues — it describes a volume/governance-capacity problem.

</details>

---

**Q4.** A team has generated a long list of 40 candidate generative AI use cases. Which set of criteria is MOST appropriate for down-selecting this list to a short pilot slate of 4-6 candidates?

A) Select use cases scoring well on both projected business value and feasibility (data readiness, risk, sponsorship, effort), while ensuring functional diversity across the portfolio
B) Select only use cases with the highest technical novelty, regardless of business sponsor or data availability
C) Select use cases in the order they were submitted, to be fair to all business units
D) Select only the single highest-value use case and fund it exclusively until complete

<details>
<summary>Answer</summary>

**Correct: A**

The standard down-selection approach combines the value/feasibility matrix score with a portfolio lens (spreading bets across functions) so the shortlist contains both quick wins and a few strategic bets rather than clustering all resources in one area.

**Why the others are wrong:**
- Technical novelty ignores business value and feasibility, the two core prioritization axes, and can favor interesting-but-low-impact projects.
- Submission order is arbitrary and ignores value/feasibility scoring entirely.
- Funding a single use case exclusively abandons the portfolio approach and creates concentration risk if that one bet fails or stalls.

</details>

---

**Q5.** During feasibility scoring, a use case involves unstructured, inconsistent legal contract data scattered across multiple unlinked repositories with no existing metadata tagging. How should this data readiness issue be reflected in the prioritization matrix?

A) Ignore it, since generative AI models can work with any format of data without preprocessing
B) Lower the feasibility score for this use case, since poor data readiness increases effort and risk even if projected business value is high
C) Increase the business value score to compensate for the data issue
D) Remove data readiness from consideration entirely, since it is not a valid feasibility input

<details>
<summary>Answer</summary>

**Correct: B**

Data readiness (structure, accessibility, quality, governance) is one of the core feasibility inputs; poor readiness directly increases implementation effort and risk and should pull the feasibility axis down regardless of how high the value axis is.

**Why the others are wrong:**
- Unstructured, unlinked, untagged data still requires significant preprocessing/integration work — it is not readiness-agnostic.
- Business value and feasibility are independent axes; a data problem is a feasibility issue and should not artificially inflate the value score.
- Data readiness is explicitly one of the standard feasibility inputs alongside risk and sponsorship, not something to exclude.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q6.** A company wants to build a balanced generative AI pilot portfolio rather than clustering every pilot in one department. Which configuration BEST reflects a portfolio-balanced approach?

A) 6 pilots, all in the marketing department, covering content generation only
B) 1 large strategic bet in IT with no quick wins
C) 5 pilots spread across marketing, customer support, finance, and operations, mixing 3 quick wins with 2 higher-value strategic bets
D) 20 small pilots spread evenly across every department to maximize coverage

<details>
<summary>Answer</summary>

**Correct: C**

A balanced portfolio deliberately spreads a manageable number of pilots across multiple functions and mixes quick wins (fast, low-risk value) with strategic bets (higher value, higher effort) to diversify risk and demonstrate value across the organization.

**Why the others are wrong:**
- Concentrating all pilots in one department fails the cross-functional diversification goal of a portfolio approach.
- A single strategic bet with no quick wins creates high risk with no near-term proof points to sustain stakeholder confidence.
- 20 pilots reintroduces the pilot-paralysis risk by exceeding evaluation and governance capacity, even if spread across departments.

</details>

---

**Q7.** Which statement BEST distinguishes a 'quick win' from a 'transformational (strategic) bet' in a generative AI use-case portfolio?

A) Quick wins always use large language models, while strategic bets always use smaller fine-tuned models
B) Quick wins are only appropriate for IT departments, while strategic bets are only appropriate for customer-facing departments
C) Quick wins deliver modest but fast, low-risk value with existing data and processes, while strategic bets require significant investment, longer timelines, and higher risk but target much larger business impact or competitive differentiation
D) Quick wins and strategic bets are functionally identical and differ only in marketing terminology used to describe them

<details>
<summary>Answer</summary>

**Correct: C**

This captures the core value/effort trade-off: quick wins sit in the low-effort, moderate-value quadrant and build momentum, while strategic bets sit in the high-value, high-effort quadrant and require sustained investment and higher risk tolerance for larger payoff.

**Why the others are wrong:**
- Model size/type is an implementation detail, not the defining distinction between quick wins and strategic bets.
- The distinction is about value and effort/risk profile, not which department is involved.
- The two categories have materially different scope, timeline, risk, and value characteristics — they are not interchangeable labels.

</details>

---

**Q8.** A team is scoring 25 candidate use cases on a 1-5 scale for both business value and feasibility, then plotting them on a 2x2 matrix. Two use cases land in the exact same quadrant (high value, high feasibility) with similar scores, but the team only has capacity to pilot one this quarter. Which additional factor should break the tie?

A) Pick the use case submitted by the most senior executive, regardless of other factors
B) Pick the use case with stronger active stakeholder sponsorship and clearer ownership for driving adoption and measuring success
C) Pick whichever use case was proposed first chronologically
D) Randomly select one to avoid the appearance of bias

<details>
<summary>Answer</summary>

**Correct: B**

When value and feasibility scores tie, sponsorship strength and clear ownership are the recognized secondary tiebreaker because they predict execution success and adoption — factors the base matrix score doesn't fully capture.

**Why the others are wrong:**
- Seniority alone, without engaged sponsorship behavior, doesn't predict execution success and can introduce political bias unrelated to value or feasibility.
- Chronological order has no bearing on value, feasibility, or execution likelihood.
- Random selection discards a legitimate, well-established tiebreaker (sponsorship) that directly affects outcome likelihood.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

