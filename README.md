# claude-prompt-optimizer

**Optimal Claude Prompt Structure**

- **Role** — tell Claude who it is: *"You are a senior developer..."*
- **Context** — one tight sentence of background, only what changes the answer
- **Task** — clear imperative verb: *"List / Write / Compare / Fix..."*
- **Constraints** — format, length, tone: *"3 bullets, no preamble, plain English"*
- **Output example** (optional) — a one-line sample of what good looks like

The formula: `[Role] + [Context] + [Task] + [Constraints]`

---

**Getting the Most from Claude Free Tier**

*Token discipline*
- Start a new chat for every new topic — old messages re-read every turn
- Front-load context once, never repeat it
- Specify output format explicitly to prevent essay-length replies
- Ask one question per message, not three at once

*Usage window*
- You get a fresh 5-hour window from your first message — plan a focused session rather than drip-feeding questions all day
- Do your own rough thinking first, bring Claude a specific question — not an open exploration

*Quality*
- Use `Sonnet` (the default) — it's the strongest model on free
- If an answer is wrong, say *what* is wrong specifically rather than just "try again"
- Paste errors verbatim — Claude diagnoses exact text better than descriptions

*Workflow*
- Use Claude for **decisions and synthesis**, not raw discovery
- Chain tasks: draft → review → refine in separate focused prompts, not one mega-prompt
- Save good outputs locally — free tier has no memory across sessions by default
