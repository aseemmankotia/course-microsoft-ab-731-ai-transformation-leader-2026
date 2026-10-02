## Chapter 5 Cheat Sheet: M365 Copilot & Role/Department Experiences

### Base Microsoft 365 Copilot — Core Apps
| App | Typical Use |
|---|---|
| Word | Draft, rewrite, summarize documents |
| Excel | Analyze data, generate formulas, insights (no formal ERP grounding) |
| PowerPoint | Generate decks from documents/prompts |
| Outlook | Draft/summarize emails, prioritize inbox |
| Teams | Summarize meetings/chats, catch-up |

**Grounding:** Base Copilot grounds in the signed-in user's **Microsoft Graph** content (mail, chat, meetings, files) — always respects existing user permissions. It does NOT require manual document upload each session, and it is NOT limited to English or a single app.

### Role-Based / Department Copilot Experiences
| Offering | Grounded In | Best For |
|---|---|---|
| Copilot for Sales | CRM data (Dynamics 365 Sales / Salesforce) + Graph | Reps needing opportunity/customer context in Outlook & Teams |
| Copilot for Service | Case/service systems (Dynamics 365 Customer Service, etc.) + Graph | Contact center case summarization, suggested replies |
| Copilot for Finance | ERP data (Business Central, SAP, etc.) + Excel | Reconciliation, variance analysis, account summaries |

**Key rule:** All role-based experiences are **add-ons on top of** the base Microsoft 365 Copilot license — not standalone products.

### Choosing the Right Tool
| Business Need | Right Choice |
|---|---|
| Summarize a meeting, draft an email | Base M365 Copilot |
| Surface CRM opportunity data in Outlook/Teams | Copilot for Sales |
| Summarize support cases, suggest replies from history | Copilot for Service |
| Reconcile Excel budgets against ERP actuals | Copilot for Finance |
| Fully custom agent, proprietary DB, custom business logic | Copilot Studio |
| Multi-system workflow automation with branching | Copilot Studio / Power Automate |

### Licensing Prerequisite (Leadership-Level)
- Requires an eligible **base Microsoft 365 plan**: E3, E5, Business Standard, or Business Premium.
- Copilot is assigned as an **add-on license** per user — not sold standalone.
- Role-based add-ons (Sales/Service/Finance) require the base Copilot license **plus** connection to the relevant LOB system.

### Limitations of Out-of-the-Box Copilot
- Assists **within** core productivity apps using the user's own Graph content.
- Does **not** orchestrate complex, multi-system, conditionally-branching workflows.
- Does **not** bypass existing permission/sharing settings — grounding scope = user's actual access.
- For deep customization → **Copilot Studio** (custom agents/topics/data sources).

### Exam Traps
- Choosing base Copilot when the scenario clearly names CRM/ERP/case-management data → should be role-based offering.
- Assuming Copilot needs on-prem Exchange or manual uploads — false, it's cloud/Graph-based.
- Assuming role-based Copilot is a separate product not requiring the base license — false, it's an add-on.
- Picking Copilot Studio for simple in-app tasks (over-engineering) when base Copilot suffices.
