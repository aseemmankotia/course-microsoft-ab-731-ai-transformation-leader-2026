## Chapter 6: Copilot Chat, Business Chat, and Copilot Studio for Custom Agents — Practice Questions

**Q1.** A regional sales director wants employees to get quick answers by asking natural-language questions across Outlook, Teams, and Word without any new development effort. Which capability should the director point employees to first?

A) Copilot Studio custom agent built from scratch
B) A third-party marketplace agent purchased and integrated via APIs
C) Microsoft 365 Copilot Chat (Business Chat)
D) A custom plugin registered in Azure AI Foundry

<details>
<summary>Answer</summary>

**Correct: C**

Copilot Chat (Business Chat) is the out-of-box, cross-app conversational entry point that requires no build effort and works across Microsoft 365 apps immediately for licensed users.

**Why the others are wrong:**
- Building a custom agent is unnecessary effort for a generic cross-app Q&A need — it's a 'build' answer to an 'adopt' problem.
- Buying a marketplace agent adds cost and integration overhead not justified for a simple cross-app chat scenario.
- Azure AI Foundry plugin registration is a developer-level activity outside the scope of adopting an existing experience.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A finance team needs an agent that queries a proprietary line-of-business database, applies custom approval logic, and posts results only to a specific Teams channel used exclusively by finance. Which approach BEST fits this requirement?

A) Adopt Microsoft 365 Copilot Chat as-is
B) Buy a generic pre-built agent from the marketplace
C) Wait for a future Microsoft 365 Copilot update to add this feature
D) Build a custom agent using Copilot Studio

<details>
<summary>Answer</summary>

**Correct: D**

Custom business logic, connection to a proprietary database, and channel-specific behavior require low-code custom agent authoring, which is exactly what Copilot Studio is designed for.

**Why the others are wrong:**
- Out-of-box Copilot Chat cannot apply custom approval logic tied to a proprietary database.
- A generic marketplace agent won't have the organization's specific approval workflow or database schema built in.
- Waiting for a future update is not a valid decision-framework option and delays a solvable business need.

</details>

---

**Q3.** An IT governance board is reviewing a business unit's request to let a citizen developer publish a customer-facing Copilot Studio agent broadly. What is the MOST important governance control to apply before approval?

A) Approve immediately since Copilot Studio agents cannot access sensitive data by design
B) Deny the request outright because citizen developers should never build agents
C) Require the agent to use only pre-approved connectors and be deployed to a managed environment with DLP policies enforced
D) Require the agent to be rebuilt entirely by professional developers in Azure AI Foundry before any review

<details>
<summary>Answer</summary>

**Correct: C**

Governance for custom agents centers on environment management and Data Loss Prevention (DLP) policies within the Power Platform admin center to control connector usage and data exposure before broad publication.

**Why the others are wrong:**
- Copilot Studio agents can absolutely connect to sensitive data sources, so this assumption is false and risky.
- Outright denial ignores the legitimate low-code build option in the decision framework and blocks business value.
- Forcing a full rebuild in Azure AI Foundry is unnecessary escalation; governance controls, not a full re-platform, are the correct first step.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** Which of the following is a defining characteristic that differentiates Copilot Studio from Microsoft 365 Copilot in the build/buy/adopt framework?

A) Copilot Studio only works with Microsoft Teams and no other channel
B) Microsoft 365 Copilot cannot be used unless Copilot Studio is also licensed
C) Copilot Studio enables low-code/no-code creation of custom, purpose-built agents with tailored data sources and logic
D) Copilot Studio requires a full professional development team and cannot be used by business users

<details>
<summary>Answer</summary>

**Correct: C**

Copilot Studio's core value proposition is enabling business users and makers to build custom agents with tailored connectors, topics, and logic without needing full software engineering resources.

**Why the others are wrong:**
- Copilot Studio agents can be published to multiple channels, not just Teams.
- Microsoft 365 Copilot and Copilot Studio are licensed and adopted independently of each other.
- Copilot Studio is explicitly positioned as low-code/no-code, usable by makers, not requiring a professional dev team.

</details>

---

**Q5.** A pilot custom agent built by a single department in Copilot Studio has proven valuable and other departments now want to use it. What is the recommended next step in the handoff process?

A) Transition the agent into an IT-governed environment with proper ALM, monitoring, and catalog listing for enterprise use
B) Let each department copy the agent into their own unmanaged personal environment
C) Rebuild the entire agent as a Microsoft 365 Copilot feature request
D) Keep the agent exactly as-is in the original maker's personal environment indefinitely

<details>
<summary>Answer</summary>

**Correct: A**

Scaling a successful pilot requires moving it into an enterprise-managed environment with application lifecycle management (ALM), monitoring, and governance so it can be reliably supported and reused.

**Why the others are wrong:**
- Unmanaged copies across departments create governance gaps, duplicated maintenance, and inconsistent data access controls.
- A feature request to Microsoft doesn't address the immediate organizational need or the existing working solution.
- Leaving it in a personal environment blocks enterprise-grade support, security review, and scaling.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q6.** Which cost/complexity trade-off is MOST accurate when comparing adopting Microsoft 365 Copilot Chat versus building a custom agent in Copilot Studio?

A) Both options have identical cost and complexity regardless of use case
B) Copilot Chat is free with no per-user licensing considerations while Copilot Studio has no cost at all
C) Building in Copilot Studio always costs less than adopting because it eliminates the need for any Microsoft 365 licensing
D) Adopting Copilot Chat generally has lower complexity and incremental cost since it's already available, while building in Copilot Studio adds maker effort, connector configuration, and consumption-based costs

<details>
<summary>Answer</summary>

**Correct: D**

Adopting an existing experience (Copilot Chat) requires no build effort and leverages existing licensing, while custom agent development in Copilot Studio introduces maker time, connector setup, testing, and consumption-based billing for agent usage.

**Why the others are wrong:**
- Cost and complexity clearly differ based on whether a solution is adopted as-is or custom built.
- Microsoft 365 Copilot Chat still involves licensing tiers and Copilot Studio does have consumption-based costs, so this statement is inaccurate.
- Copilot Studio agents still require underlying Microsoft 365/Power Platform licensing in most enterprise scenarios, so this claim overstates savings.

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** A department wants an agent that summarizes customer support tickets from a third-party ticketing system not connected to Microsoft 365 data, with logic specific to their support workflow. According to the decision framework, this scenario is best classified as which type of solution?

A) Adopt — use Microsoft 365 Copilot Chat directly
B) Buy — purchase a pre-built agent with no configuration needed
C) None of the above; this requirement cannot be met with any Copilot offering
D) Build — use Copilot Studio to create a tailored custom agent with appropriate connectors and logic

<details>
<summary>Answer</summary>

**Correct: D**

A workflow-specific need tied to a non-Microsoft data source with custom summarization logic is a textbook 'build' scenario suited to Copilot Studio's low-code connector and topic authoring.

**Why the others are wrong:**
- Copilot Chat is not designed to natively integrate deeply with arbitrary third-party ticketing systems without custom configuration.
- A generic pre-built agent likely won't match the department's specific workflow logic without customization, undermining the 'buy as-is' premise.
- Copilot Studio explicitly supports custom connectors, making this requirement solvable within the Microsoft ecosystem.

</details>

---

**Q8.** In leadership terms, what does Copilot Studio primarily enable for an organization?

A) The ability for business users to create custom, purpose-specific conversational agents using low-code/no-code tools without deep software engineering resources
B) The ability to fine-tune foundation models using proprietary training data at the infrastructure level
C) Automatic migration of all on-premises applications to the cloud
D) Replacement of Microsoft 365 Copilot licensing requirements entirely

<details>
<summary>Answer</summary>

**Correct: A**

From a leadership perspective, Copilot Studio's value is democratizing custom agent creation for business users through low-code/no-code tooling, not requiring a full engineering team.

**Why the others are wrong:**
- Model fine-tuning at the infrastructure level is a data science/engineering activity handled through platforms like Azure AI Foundry, not Copilot Studio's leadership framing.
- Copilot Studio has no relationship to on-premises application migration.
- Copilot Studio and Microsoft 365 Copilot licensing are separate and complementary, not mutually exclusive replacements.

</details>

---

