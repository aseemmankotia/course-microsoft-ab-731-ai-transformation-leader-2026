## Chapter 8: Copilot Across the Ecosystem: Grounding, Data Protection, and Licensing — Practice Questions

**Q1.** A bank's leadership team is evaluating Microsoft 365 Copilot but is worried that employee prompts could be used to retrain the underlying foundation models. Which statement correctly describes what Enterprise Data Protection (EDP) promises?

A) Prompts and responses are sent to a third-party moderation service before being deleted after 30 days
B) Prompts are anonymized and pooled across all Microsoft 365 tenants to improve the shared model
C) Prompts are only protected if the organization purchases a separate Microsoft Purview add-on
D) Prompts and responses are not used to train the foundation LLMs and remain within the Microsoft 365 tenant boundary

<details>
<summary>Answer</summary>

**Correct: D**

EDP is the data protection promise bundled with licensed Microsoft 365 Copilot: prompts/responses aren't used to train the foundation models and stay inside the tenant's existing compliance boundary.

**Why the others are wrong:**
- There is no third-party moderation-then-delete workflow described in Microsoft's commitments
- Data is never pooled across tenants to improve a shared model — that would violate the tenant isolation promise
- EDP is included with the Copilot license itself, not a separate Purview purchase

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q2.** A retail company's sales reps want an AI assistant embedded directly inside their CRM to draft follow-up emails and summarize open opportunities. Which product should the leadership team select?

A) Microsoft Copilot (Copilot Chat, consumer-facing)
B) GitHub Copilot Business
C) Microsoft Security Copilot
D) Copilot for Dynamics 365

<details>
<summary>Answer</summary>

**Correct: D**

Copilot for Dynamics 365 is embedded directly in apps like Sales and Customer Service, drafting emails and summarizing opportunities/cases.

**Why the others are wrong:**
- Copilot Chat is a general web/chat experience, not embedded in CRM records
- GitHub Copilot Business targets developers writing code, not sales reps
- Security Copilot is built for SOC/security operations, not sales workflows

</details>

---

**Q3.** A security operations center wants an AI assistant that integrates with Microsoft Sentinel and Defender to help analysts investigate incidents faster. Which product fits this requirement?

A) Microsoft Security Copilot
B) Copilot for Dynamics 365
C) Microsoft 365 Copilot
D) GitHub Copilot Enterprise

<details>
<summary>Answer</summary>

**Correct: A**

Security Copilot is purpose-built for SOC teams, integrating with Sentinel, Defender, Entra, and Purview to assist with investigations.

**Why the others are wrong:**
- Dynamics 365 Copilot is for CRM/ERP workflows, not security investigations
- Microsoft 365 Copilot grounds in productivity content (email, docs, chats), not security telemetry
- GitHub Copilot Enterprise is a developer coding assistant, unrelated to SOC tooling

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q4.** An engineering organization wants developers to get AI code suggestions that are fine-tuned on the company's own private repositories, plus AI chat directly on GitHub.com. Which licensing tier is required?

A) GitHub Copilot Individual
B) GitHub Copilot Business
C) GitHub Copilot Enterprise
D) Microsoft 365 Copilot add-on

<details>
<summary>Answer</summary>

**Correct: C**

GitHub Copilot Enterprise adds org-specific fine-tuning on private codebases and chat/PR summaries on GitHub.com — features not available at the Individual or Business tier.

**Why the others are wrong:**
- Individual is a personal, non-org license with no fine-tuning on company repos
- Business provides policy management and org-wide licensing but not custom fine-tuning on private repos
- Microsoft 365 Copilot is unrelated to code repositories — it grounds in Microsoft Graph productivity content

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q5.** An IT admin attempts to assign a Microsoft 365 Copilot license to a user but the assignment fails. What is the most likely cause?

A) The user has not enabled multi-factor authentication
B) The user's mailbox is larger than 50 GB
C) The tenant has not enabled the EU Data Boundary
D) The user lacks an eligible base license such as Microsoft 365 E3, E5, Business Standard, or Business Premium

<details>
<summary>Answer</summary>

**Correct: D**

Microsoft 365 Copilot is an add-on license that requires an eligible qualifying Microsoft 365 base plan before it can be assigned.

**Why the others are wrong:**
- MFA status does not gate Copilot license assignment
- Mailbox size is unrelated to Copilot licensing eligibility
- The EU Data Boundary is a data residency setting, not a licensing prerequisite

</details>

---

**Q6.** A user wants their chats in Microsoft Copilot (the free chat experience) protected under Commercial Data Protection. What must they do?

A) Purchase a standalone Microsoft 365 Copilot license
B) Sign in using their personal Microsoft account
C) Enable sensitivity labels in Microsoft Purview
D) Sign in using their organizational Entra ID (work/school) account

<details>
<summary>Answer</summary>

**Correct: D**

Commercial Data Protection applies automatically when the user is signed in with an Entra ID (work/school) account — no separate Copilot license purchase is required.

**Why the others are wrong:**
- A paid Copilot license enables EDP, not CDP, and isn't required for CDP
- Signing in with a personal account puts the user in the consumer experience without CDP
- Sensitivity labels are a separate Purview governance control, unrelated to enabling CDP

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q7.** What does 'grounding' mean in the context of Microsoft 365 Copilot?

A) The process by which Copilot references a user's own organizational content via Microsoft Graph, respecting existing permissions
B) The process of fine-tuning the foundation LLM on the organization's entire tenant data
C) The process of physically hosting Copilot infrastructure in the customer's own datacenter
D) The process of restricting Copilot to only public web search results

<details>
<summary>Answer</summary>

**Correct: A**

Grounding is the conceptual mechanism where Copilot pulls in relevant emails, chats, and files the signed-in user can already access via Microsoft Graph, without elevating permissions.

**Why the others are wrong:**
- Grounding does not involve retraining or fine-tuning the model on tenant data
- Grounding is a data-access concept, not a hosting/infrastructure model
- Copilot's grounding pulls from organizational content, not just public web results

> ⚠️ Frequently missed on the exam — read the options carefully.

</details>

---

**Q8.** Before rolling out Microsoft 365 Copilot, a leadership team wants to ensure compliance requirements are met. Which question is MOST important to ask about tenant boundaries?

A) How many storage accounts does the organization currently use?
B) Does any prompt or response data cross the tenant boundary or leave the region defined by the organization's data residency commitments?
C) How many GitHub repositories exist in the organization?
D) What color scheme does the Copilot UI use in Microsoft 365 apps?

<details>
<summary>Answer</summary>

**Correct: B**

Data residency and tenant boundary questions — whether prompt/response data stays within the organization's committed region/tenant — are the key compliance question leaders must ask before rollout.

**Why the others are wrong:**
- Storage account count is an infrastructure detail unrelated to Copilot data residency
- GitHub repository count relates to developer tooling, not M365 Copilot's data boundary
- UI appearance has no compliance or data protection relevance

</details>

---

