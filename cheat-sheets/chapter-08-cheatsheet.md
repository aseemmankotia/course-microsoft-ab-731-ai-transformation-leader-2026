## Chapter 8 Cheat Sheet: Copilot Ecosystem, Grounding & Data Protection

### Grounding (Conceptual)
Copilot references the **signed-in user's own organizational content** (email, Teams chats, SharePoint/OneDrive files) via **Microsoft Graph** and the Semantic Index.
- Never elevates permissions — user must already have access to the content.
- Exam trap: "Copilot can read anything in the tenant" → FALSE.

### Data Protection: EDP vs CDP

| Feature | Enterprise Data Protection (EDP) | Commercial Data Protection (CDP) |
|---|---|---|
| Applies to | Licensed Microsoft 365 Copilot | Microsoft Copilot Chat (free experience) |
| Requirement | Paid Copilot add-on seat | Sign in with Entra ID work/school account |
| Grounding in Graph data | Yes | No |
| Training on prompts | Never | Never |
| Tenant boundary | Full compliance boundary | Chat not saved, not visible to MS staff |

### Awareness-Level Copilot Integrations

| Product | Purpose | Audience |
|---|---|---|
| Copilot for Dynamics 365 | Draft emails, summarize opportunities/cases | Sales, Customer Service teams |
| Microsoft Security Copilot | Investigate incidents with Sentinel/Defender/Entra/Purview | SOC analysts |
| GitHub Copilot | AI pair programmer in IDE / GitHub.com | Developers (leadership decides licensing) |

### GitHub Copilot Licensing Tiers

| Tier | Key Feature |
|---|---|
| Individual | Personal use, no org fine-tuning |
| Business | Org-wide policy management, seat control |
| Enterprise | Fine-tuned on private repos, chat + PR summaries on GitHub.com |

### Licensing Prerequisites for Rollout
- Microsoft 365 Copilot = **add-on**; requires eligible base plan: M365 E3, E5, Business Standard, or Business Premium.
- Security Copilot = standalone, **consumption-based** billing per Security Compute Unit (SCU) — not a per-user seat.
- GitHub Copilot = separate licensing track from Microsoft 365 Copilot; a portfolio/licensing decision even though used by technical teams.

### Data Residency / Tenant Boundary Questions for Leadership
1. Does prompt/response data cross the tenant boundary?
2. Is the organization's committed data region (e.g., EU Data Boundary) honored?
3. Do connected plugins/connectors send data outside the tenant?
4. Which Copilot experience (paid vs. free chat) is in use, and which protection (EDP vs CDP) applies?

### Exam Traps
- Confusing EDP (paid, Graph-grounded) with CDP (free, chat-only).
- Assuming grounding bypasses permissions — it never does.
- Assuming GitHub Copilot is only a developer-tooling decision — it's also a licensing/portfolio decision for leadership.
- Assuming Security Copilot uses per-user licensing — it's consumption-based (SCUs).
