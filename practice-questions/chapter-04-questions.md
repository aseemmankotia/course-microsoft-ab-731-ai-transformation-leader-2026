## Chapter 4: Responsible AI Governance, Risk, and Regulatory Awareness at the Organizational Level — Practice Questions

**Q1.** An HR department wants to deploy a generative AI tool to automatically screen and rank job candidates' resumes. Under the EU AI Act's risk-tiering framework, how should organizational leadership classify this use case?

A) Minimal risk, since it only summarizes text rather than making final hiring decisions
B) High risk, because it affects access to employment and requires enhanced oversight obligations
C) Unacceptable risk, so it must be banned outright regardless of safeguards
D) Limited risk, requiring only a disclosure that AI was used

<details>
<summary>Answer</summary>

**Correct: B**

The EU AI Act explicitly classifies AI systems used in employment, including recruitment and candidate screening/ranking, as high-risk, triggering requirements like human oversight, documentation, and risk management — a leadership accountability, not just an engineering task.

**Why the others are wrong:**
- Ranking candidates directly influences employment outcomes, so it is not minimal risk regardless of the 'summarization' framing
- Employment screening is not on the banned/unacceptable list (e.g., social scoring, manipulative techniques) — it is regulated, not prohibited
- Limited risk (transparency-only obligations) applies to things like chatbots disclosing they are AI, not to systems that materially affect employment decisions

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A CEO is told the company's new generative AI assistant occasionally 'hallucinates' incorrect facts. Which response BEST reflects a governance-level (leadership) approach rather than a purely technical fix?

A) Set organizational policy requiring human review of AI outputs in customer-facing decisions and clear disclosure of AI limitations to users
B) Instruct engineers to increase the model's context window to reduce hallucinations
C) Wait for the vendor to release a more accurate model version
D) Restrict AI use to internal employees only until hallucinations are technically eliminated

<details>
<summary>Answer</summary>

**Correct: A**

Leadership governs AI risk through policy: mandating human review, setting accountability for outputs, and being transparent with stakeholders about known limitations — this addresses risk even though hallucinations can't be fully eliminated technically.

**Why the others are wrong:**
- This is an engineering-level technical control, not a governance decision, and doesn't eliminate hallucination risk on its own
- Waiting for a vendor fix ignores the organization's own accountability and risk obligations right now
- Restricting to internal use doesn't address the underlying governance need for oversight and disclosure, and hallucinations can occur internally too

</details>

---

**Q3.** Which Responsible AI pillar is MOST directly concerned with an organization's ability to explain how and why an AI system produced a particular output to regulators, customers, or auditors?

A) Inclusiveness
B) Transparency
C) Reliability and safety
D) Fairness

<details>
<summary>Answer</summary>

**Correct: B**

Transparency covers explainability, disclosure of AI use, and the ability to communicate how a system arrived at a decision — a core governance concern for audits and regulatory inquiries.

**Why the others are wrong:**
- Inclusiveness concerns designing AI to serve diverse groups of people, not explainability of outputs
- Reliability/safety concerns consistent, safe operation of the system, not explaining its reasoning
- Fairness concerns avoiding discriminatory or biased outcomes, which is related but distinct from explainability

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** A company relies solely on its IT security team's technical access controls to manage all generative AI risk, with no executive-level oversight body. What is the PRIMARY governance gap in this approach?

A) IT security teams are not capable of implementing any technical controls related to AI
B) Technical access controls are unnecessary if the AI model itself is considered safe
C) There is no cross-functional structure (legal, compliance, business, and technical stakeholders) to set policy, assess business risk, and ensure accountability beyond technical safeguards
D) The organization should instead outsource all AI risk management to its AI vendor

<details>
<summary>Answer</summary>

**Correct: C**

Effective AI governance requires a cross-functional oversight structure (e.g., an AI governance board) that sets policy guardrails, evaluates legal/regulatory/reputational risk, and assigns accountability — technical controls alone don't cover policy, ethics, or regulatory compliance.

**Why the others are wrong:**
- IT security teams can implement effective technical controls; the issue is scope, not competence
- Technical safeguards remain necessary even with policy oversight — the two are complementary, not substitutes
- Vendors can support risk management but cannot assume the organization's own regulatory and accountability obligations

</details>

---

**Q5.** Which of the following is an example of a POLICY guardrail, as distinct from a technical control, for managing generative AI risk?

A) Enabling content filtering thresholds on a model API
B) Configuring rate limiting on API calls
C) Enabling encryption at rest for training data
D) A board-approved policy requiring all customer-facing AI content to be reviewed and disclosed as AI-generated before publication

<details>
<summary>Answer</summary>

**Correct: D**

A board-approved review-and-disclosure requirement is an organizational policy decision that governs human behavior and process — a governance guardrail — rather than a system-level technical configuration.

**Why the others are wrong:**
- Content filtering thresholds are a technical/configuration control implemented in the system itself
- Rate limiting is a technical control managing system usage, not an organizational policy
- Encryption at rest is a technical security control, not a governance policy about human review or disclosure

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q6.** Under the EU AI Act, which use case falls into the 'unacceptable risk' category and is banned outright, regardless of safeguards implemented?

A) A government social scoring system that evaluates citizens' trustworthiness based on behavior
B) A generative AI chatbot used for customer support that discloses it is an AI system
C) An AI system used to summarize internal meeting notes
D) An AI system used in a hospital to help triage low-risk versus urgent patient cases with human doctor oversight

<details>
<summary>Answer</summary>

**Correct: A**

Social scoring systems by public authorities are explicitly listed under the EU AI Act as an unacceptable-risk practice and are prohibited, along with things like manipulative subliminal techniques and exploitation of vulnerabilities.

**Why the others are wrong:**
- A disclosed customer-support chatbot is a limited-risk use case requiring transparency, not a ban
- Internal note summarization is typically minimal risk with no specific regulatory obligations
- Medical triage AI is high risk (falls under critical/essential services), requiring oversight and documentation — not prohibited

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** A company deploys a generative AI tool that monitors employee emails and chat messages to flag productivity concerns. From a transparency and accountability standpoint, what should leadership prioritize FIRST?

A) Deploying the tool silently to get an unbiased baseline of employee behavior before informing anyone
B) Clearly disclosing to employees that AI monitoring is in place, its purpose, and how outputs will be used, along with an accountable owner for decisions made from it
C) Delaying any employee notification until after the first year of data has been collected
D) Allowing only the vendor's terms of service to define usage boundaries

<details>
<summary>Answer</summary>

**Correct: B**

Responsible AI governance requires transparent disclosure to employees about AI monitoring and its purpose, plus a named accountable owner for how outputs are used — building trust and meeting emerging legal disclosure obligations.

**Why the others are wrong:**
- Silent monitoring undermines trust and likely violates transparency obligations and employment law in many jurisdictions
- Delaying disclosure for a year is not a transparency practice and increases legal and reputational risk
- Relying solely on vendor terms abdicates the organization's own accountability for how the tool is used internally

</details>

---

**Q8.** Which statement BEST reflects setting realistic stakeholder expectations about generative AI limitations at the leadership level?

A) Assuring stakeholders that once fine-tuned, the model will never hallucinate or produce biased output again
B) Communicating that generative AI can produce plausible but incorrect outputs (hallucination) and may reflect biases from training data, so human review and monitoring remain necessary parts of the process
C) Avoiding any discussion of AI limitations with stakeholders to prevent reduced confidence in the technology
D) Delegating all limitation disclosures to the engineering team so leadership can focus solely on business outcomes

<details>
<summary>Answer</summary>

**Correct: B**

Leadership's role is to set honest, realistic expectations that generative AI has inherent limitations (hallucination, bias) and that ongoing human oversight is required — this is a governance and trust-building responsibility, not a technical detail to hide.

**Why the others are wrong:**
- No amount of fine-tuning eliminates hallucination or bias risk entirely; promising this misleads stakeholders
- Avoiding the topic creates larger trust and liability problems if failures surface later
- Limitation communication is a leadership/governance responsibility since it involves risk, trust, and accountability, not just engineering detail

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

