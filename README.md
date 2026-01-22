# Competitor Intelligence Agent

Competitor intelligence that runs while you sleep. Configure once, receive weekly briefings with what changed, threat levels, and recommendations.

[Read the full story →](link-to-article)

---

## Get Started

**Time:** ~15 minutes

**Step 1: Install the tools** (skip what you already have)

- Git — [git-scm.com](https://git-scm.com)
- Claude Code:
  - Mac: `curl -fsSL https://claude.ai/install.sh | bash`
  - Windows: `irm https://claude.ai/install.ps1 | iex`

**Step 2: Run the agent**

Paste this into Terminal (Mac) or PowerShell (Windows):
```
git clone https://github.com/ryan-hennebry/competitor-intelligence-agent && cd competitor-intelligence-agent && claude
```

---

## The Onboarding Conversation

The agent asks a few questions, one at a time:

1. **Your company** — Paste your URL or describe what you do. The agent researches your positioning and asks you to confirm.

2. **Competitors** — The agent suggests competitors based on your positioning. Accept or adjust.

3. **What to track** — Defaults: positioning changes, partnerships, features, hiring. Accept or customize.

Then your first briefing generates.

---

## After Setup

After the briefing, the agent suggests next steps based on what it found:

- If it spotted a high threat: "Want a battle card for [competitor]?"
- If it found gaps: "Should I draft messaging for these weaknesses?"
- If you want automation: "Set up weekly briefings?"

Or just talk to it:
- "Add [competitor]"
- "What changed since last week?"
- "Compare [competitor] over time"

For automatic weekly briefings, say "Set up scheduled briefings" — the agent walks you through delivery options (email, Slack, or files).

