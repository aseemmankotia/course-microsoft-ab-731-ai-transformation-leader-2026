## Chapter 10 Cheat Sheet: Copilot CoE & Governance Guardrails

### CoE Purpose
A cross-functional structure that **governs, enables, and scales** Copilot adoption safely. Not a helpdesk; not a prompt-writing team.

### Centralized vs Federated
| Model | How it works | Best fit | Risk |
|---|---|---|---|
| Centralized | Single team owns all approvals/security review/audit trail | Regulated industries (healthcare, finance), strict audit needs | Can bottleneck large orgs |
| Federated | Central policy guardrails + BU-level champions/local approvals | Large, diverse orgs, many BUs, need for speed | Requires strong shared guardrails to avoid drift |
| No CoE | Each dept self-governs | Not recommended | Inconsistent security, no violation detection |

**Exam trigger phrases:**
- "strict audit requirements across all departments" → centralized
- "12 business units, different risk profiles, bottleneck complaints" → federated

### Governance Guardrail Categories
1. **Usage policies** — what Copilot may be used for
2. **Approved-use list** — vetted agents/use cases + prohibited data types
3. **Data-handling rules** — PII, classification, retention

### Roles Typically on a CoE
| Role | Responsibility |
|---|---|
| IT | Platform config, licensing, technical enablement |
| Security | Threat/risk review of agents and integrations |
| Compliance/Legal | Regulatory + data-handling oversight |
| HR | Workforce impact, training, change management |
| Business Unit Leads | Represent functional needs/use cases |

### CoE Role in Vetting New Agents
Before scaling any new agent/use case (especially ones touching PII or sensitive data):
1. Security review
2. Data-handling/compliance review
3. Check against approved-use list
4. Formal approval before broad rollout

**Wrong-answer pattern:** "Deploy immediately, review later" — always wrong when PII/sensitive data is involved.

### Measuring CoE Effectiveness
| Metric | Signals |
|---|---|
| Time-to-approval | Governance isn't bottlenecking adoption |
| Policy violation rate post-rollout | Guardrails are actually working |
| ❌ License count, marketing spend, ticket volume | Adoption budget/support metrics — NOT governance effectiveness |

### Common Exam Traps
- Assuming Microsoft's platform enforces org governance automatically — it does not; guardrails are the customer's responsibility.
- Treating "no CoE / fully independent departments" as a valid low-risk option — it isn't.
- Confusing HR's role (people/change management) with Compliance's role (data/regulatory oversight).
- Picking a single-function team (e.g., "Marketing only") as representing "the CoE" — CoE is cross-functional by definition.
