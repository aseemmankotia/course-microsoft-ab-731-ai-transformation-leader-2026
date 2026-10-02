## Chapter 8: Copilot Across the Ecosystem: Grounding, Data Protection, and Licensing — Flashcards

| # | Front (Question) | Back (Answer) |
|---|-----------------|---------------|
| 1 | What does Enterprise Data Protection (EDP) guarantee for Microsoft 365 Copilot? | Prompts/responses aren't used to train foundation LLMs and stay within the Microsoft 365 tenant boundary, covered by existing compliance commitments. Requires a licensed Microsoft 365 Copilot seat. |
| 2 | What does Commercial Data Protection (CDP) guarantee in Microsoft Copilot Chat? | Chat data isn't saved, Microsoft employees can't view it, and it's not used for model training — applies automatically when signed in with an Entra ID work/school account, no paid license required. |
| 3 | EDP vs CDP — key difference? | EDP = paid Microsoft 365 Copilot, grounded in organizational Graph data, full tenant-boundary protection. CDP = free-tier protection for the chat experience, no Graph grounding. |
| 4 | What is 'grounding' in Microsoft 365 Copilot? | The process of Copilot referencing a user's own organizational content (email, chats, files) via Microsoft Graph — always respecting existing permissions. |
| 5 | Can grounding bypass a user's existing permissions? | No — Copilot only surfaces content the signed-in user already has access to. Exam trap: assuming Copilot 'sees everything' in the tenant. |
| 6 | What is Copilot for Dynamics 365 (awareness level)? | Embedded AI assistant inside D365 apps (Sales, Customer Service) that drafts emails, summarizes opportunities/cases, and suggests replies. |
| 7 | How is Microsoft Security Copilot priced? | Consumption-based — billed hourly per Security Compute Unit (SCU), not a flat per-user license like Microsoft 365 Copilot. |
| 8 | What are the three GitHub Copilot licensing tiers? | Individual, Business, Enterprise. Enterprise adds org-specific fine-tuning on private repos, chat on GitHub.com, and PR summaries. |
| 9 | What base license is required before assigning the Microsoft 365 Copilot add-on? | An eligible qualifying plan — Microsoft 365 E3, E5, Business Standard, or Business Premium. Copilot is an add-on, not standalone. |
| 10 | What tenant-boundary questions should leadership ask before an M365 Copilot rollout? | Where is prompt/response data processed, does it cross the tenant boundary, is the region/EU Data Boundary commitment honored, and do connected plugins send data outside the tenant? |
| 11 | Is GitHub Copilot an awareness-level or hands-on topic for this exam? | Awareness/licensing-portfolio level — leaders need to know it exists and its tiers, not write code with it. |
| 12 | Common exam trap about Copilot data protection? | Assuming all Copilot experiences share one protection model. CDP applies to the free chat experience; EDP applies only to licensed Microsoft 365 Copilot. |
