## Chapter 6 Cheat Sheet: Copilot Chat, Business Chat, and Copilot Studio

### Core Definitions
| Term | What It Is | Framework Role |
|---|---|---|
| Copilot Chat / Business Chat | Cross-app conversational entry point across Microsoft 365 (Outlook, Teams, Word, etc.) | **Adopt** |
| Copilot Studio | Low-code/no-code platform to build custom conversational agents with tailored connectors and logic | **Build** |
| Pre-built/marketplace agent | Vendor-supplied agent addressing a common need with little/no customization | **Buy** |

### Build vs Buy vs Adopt Decision Framework
| Choose... | When... |
|---|---|
| **Adopt** | Need is generic, cross-app, already covered by out-of-box Copilot Chat |
| **Buy** | A pre-built agent already closely matches the requirement |
| **Build** | Need involves custom logic, proprietary/non-Microsoft data sources, or a unique workflow |

### Scenario Cues
- "Ask questions across Outlook/Teams/Word" → **Adopt** (Copilot Chat)
- "Custom database + approval logic + specific channel" → **Build** (Copilot Studio)
- "Vendor solution already does this" → **Buy**

### Governance Checklist for Custom Agents
1. Deploy to a **managed environment** (not personal/unmanaged)
2. Enforce **DLP policies** via Power Platform admin center
3. Restrict to **approved connectors**
4. Require **review before broad publication**

### Cost/Complexity Trade-offs
| Option | Effort | Cost Model |
|---|---|---|
| Adopt (Copilot Chat) | Minimal — no build needed | Included in Microsoft 365 Copilot license |
| Buy (pre-built agent) | Low-moderate — configuration only | Vendor/marketplace pricing |
| Build (Copilot Studio) | Higher — maker time, connectors, testing | Consumption-based (messages/sessions) + underlying licensing |

### Pilot-to-Enterprise Handoff
1. Pilot succeeds in a maker's personal/dev environment
2. Move to **IT-governed environment**
3. Apply **ALM** (application lifecycle management)
4. Enable **monitoring**
5. List in **agent catalog** for org-wide reuse

### Exam Traps
- Confusing Copilot Chat (adopt, out-of-box) with Copilot Studio (build, custom) — they are NOT the same tier.
- Assuming Copilot Studio agents can't touch sensitive/proprietary data — they can, hence governance is required.
- Choosing "Build" when "Adopt" would meet the need with far less cost/complexity.
- Forgetting the handoff step: pilots must move to a **governed** environment before enterprise scaling.
