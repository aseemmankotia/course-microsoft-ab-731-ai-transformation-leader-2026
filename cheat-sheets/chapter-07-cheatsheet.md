## Chapter 7 Cheat Sheet: Agents, Agent Store & Microsoft Foundry (Leadership Level)

### Core Distinction
| Concept | Purpose | Who Uses It | Effort |
|---|---|---|---|
| **Agent Store** | Discover & deploy pre-built agents for common tasks | Business leaders, non-technical staff | Low — no dev needed |
| **Microsoft Foundry** | Build custom/advanced AI solutions & agents | Developers, data scientists | High — dev resources required |
| **Foundry Tools** | Pre-built AI building blocks (vision, language, speech, doc intelligence) used inside Foundry | Developers building custom solutions | N/A — components, not standalone |

### Copilot Chat vs Agent
| Feature | Copilot Chat | Agent |
|---|---|---|
| Trigger | User prompt only | Prompt, schedule, or event |
| Task scope | Single-turn conversational response | Multi-step task execution |
| Autonomy | None — reactive | Autonomous or semi-autonomous |
| Human checkpoint | Every turn (inherent) | Optional, at defined steps only |

### Autonomy Spectrum
- **Autonomous agent** → completes task end-to-end, no human checkpoint
- **Semi-autonomous agent** → executes steps, pauses for human approval before high-risk actions (human-in-the-loop)

### Decision Rule: Agent Store vs Foundry
- Need matches an existing common task + speed matters → **Agent Store**
- Need requires proprietary data/model, custom orchestration, or no existing agent fits → **Foundry initiative**

### Third-Party Agent Vetting Checklist (Leadership)
1. Publisher verification status
2. Data/permission scopes requested by the agent
3. Compliance certifications relevant to industry/region
4. Alignment with existing DLP and governance policies
5. Store presence ≠ organizational risk clearance — still requires internal review

### Governance Controls to Configure
- Restrict which agents can be installed org-wide
- Scope data/permission access per agent
- Maintain DLP policy alignment — never bypass for performance
- Avoid blanket full-admin access grants to any agent

### Common Exam Traps
- Assuming Agent Store presence = full compliance vetting done (it doesn't)
- Confusing Copilot chat's reactive nature with an agent's autonomous/event-driven behavior
- Choosing Foundry for a need an existing pre-built agent already solves (over-engineering)
- Choosing Agent Store for a need requiring proprietary models/data (under-engineering)
