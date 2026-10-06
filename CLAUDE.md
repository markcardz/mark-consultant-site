# Claude Project Instructions for AI Consultant Training

## Auto-Tracker Updates

**When to trigger:** After Mark completes ALL tasks in a day's checklist (when he confirms the day is done).

**Tracker doc:**
- Artifact URL: `https://claude.ai/artifact/C1zgvhriPqY781fQCrmJYa`
- Claude Docs project ID: `593813b5-5d57-4b23-b1aa-56ad3595981b`
- Root node ID: `835668c7-cce9`
- Session prefix for all block IDs: `mr4461gndec`

**How to update (no doc read needed — use block IDs below):**
```
mcp__Claude_Docs__update(
  container={"kind": "project", "id": "593813b5-5d57-4b23-b1aa-56ad3595981b"},
  ref={"object": "node", "id": "835668c7-cce9"},
  payload={"ops": [
    {"op": "set", "target": {"kind": "blocks", "ids": ["mr4461gndec.XXXX"]}, "attrs": {"checked": true}},
    ...
  ]}
)
```

---

## Block IDs by Day

### Day 1 ✅ (all checked)
- mr4461gndec.1967 — Install VS Code, Git, Node.js and Claude Code
- mr4461gndec.2025 — Terminal basics
- mr4461gndec.2099 — Create a GitHub account
- mr4461gndec.2124 — Learn the 6 parts of an app
- mr4461gndec.2227 — Learn what an LLM is
- mr4461gndec.2289 — Teach-back + start your glossary

### Day 2 ✅ (all checked)
- mr4461gndec.2496 — Recall (10 min)
- mr4461gndec.2513 — Git basics
- mr4461gndec.2582 — Build one-page site
- mr4461gndec.2675 — Deploy on Vercel
- mr4461gndec.2738 — Teach-back + log

### Day 3 ✅ (all checked)
- mr4461gndec.2796 — Recall (10 min)
- mr4461gndec.2830 — Finish rolled-over items
- mr4461gndec.2860 — Explain 6 parts + Git out loud
- mr4461gndec.2921 — Practice restore

### Day 4 ✅ (all checked)
- mr4461gndec.3052 — Recall (10 min)
- mr4461gndec.3069 — CLAUDE.md
- mr4461gndec.3134 — Plan mode, context, permissions
- mr4461gndec.3193 — Build: contact section
- mr4461gndec.3258 — Teach-back + log

### Day 5 ✅ (all checked)
- mr4461gndec.3334 — Recall (10 min)
- mr4461gndec.3351 — File formats: CSV, JSON, markdown
- mr4461gndec.3408 — Build: Vantage files in GitHub
- mr4461gndec.3475 — Teach-back + log

### Day 6 ✅ (all checked)
- mr4461gndec.3533 — Recall (10 min)
- mr4461gndec.3567 — Spreadsheets vs databases
- mr4461gndec.3650 — Build: load data into Google Sheets
- mr4461gndec.3733 — Supabase (deferred to Phase 3)
- mr4461gndec.3824 — Teach-back + log

### Day 7 ✅ (all checked)
- mr4461gndec.3894 — Recall (10 min)
- mr4461gndec.3911 — Prompt structure
- mr4461gndec.3975 — Structured output
- mr4461gndec.4030 — Build: ticket classifier prompt
- mr4461gndec.4116 — Start prompt library
- mr4461gndec.4169 — Teach-back + log

### Day 8 ✅ (all checked)
- mr4461gndec.4226 — Recall (10 min)
- mr4461gndec.4243 — Branches, pull requests, diffs
- mr4461gndec.4320 — Practice: Claude opens PR, you merge
- mr4461gndec.4407 — Read /ship-and-watch phases
- mr4461gndec.4477 — Teach-back + log

### Day 9 ⬜
- mr4461gndec.4536 — Recall (10 min)
- mr4461gndec.4570 — Finish rolled-over items
- mr4461gndec.4600 — Rebuild Day 2 page in new repo
- mr4461gndec.4688 — Tidy your glossary

### Day 10 ⬜
- mr4461gndec.4971 — Recall (10 min)
- mr4461gndec.4988 — What an API is
- mr4461gndec.5062 — API keys and .env files
- mr4461gndec.5144 — Build: call a public API
- mr4461gndec.5218 — Teach-back + log

### Day 11 ⬜
- mr4461gndec.5275 — Recall (10 min)
- mr4461gndec.5292 — Get Claude API key, set spend limit
- mr4461gndec.5363 — Messages, models, tokens, cost
- mr4461gndec.5422 — Build: classify support tickets via API
- mr4461gndec.5500 — Measure cost per 100 tickets
- mr4461gndec.5534 — Teach-back + log

### Day 12 ⬜
- mr4461gndec.5593 — Recall (10 min)
- mr4461gndec.5628 — Main model families
- mr4461gndec.5712 — Model selection
- mr4461gndec.5814 — Off-the-shelf vs custom
- mr4461gndec.5913 — Build: rerun classifier on smaller model
- mr4461gndec.6003 — Write "Why not just use Copilot?"
- mr4461gndec.6059 — Teach-back + log

### Day 13 ⬜
- mr4461gndec.6133 — Recall (10 min)
- mr4461gndec.6150 — Prompt injection
- mr4461gndec.6275 — Data leakage, jailbreaks, hallucinations
- mr4461gndec.6357 — Build: plant malicious instruction
- mr4461gndec.6487 — Teach-back + log

### Day 14 ⬜
- mr4461gndec.6549 — Recall (10 min)
- mr4461gndec.6566 — Why AI gets things wrong
- mr4461gndec.6680 — Evals
- mr4461gndec.6773 — Build: 20 test tickets, score classifier
- mr4461gndec.6874 — Teach-back + log

### Day 15 ⬜
- mr4461gndec.6934 — Recall (10 min)
- mr4461gndec.6970 — Finish rolled-over items
- mr4461gndec.7000 — Explain API keys, model choice, prompt injection
- mr4461gndec.7083 — Tidy your glossary

### Day 16 ⬜
- mr4461gndec.7378 — Recall (10 min)
- mr4461gndec.7395 — Principles: trigger → steps → action
- mr4461gndec.7499 — Map a process on paper
- mr4461gndec.7600 — Set up n8n
- mr4461gndec.7651 — Teach-back + log

### Day 17 ⬜
- mr4461gndec.18283 — Recall (10 min)
- mr4461gndec.18300 — Build: form → Sheet → email
- mr4461gndec.18364 — Error handling
- mr4461gndec.18438 — Simulate failure
- mr4461gndec.18521 — Teach-back + log

### Day 18 ⬜
- mr4461gndec.8042 — Recall (10 min)
- mr4461gndec.8078 — Build: lead intake with AI
- mr4461gndec.8165 — Duplicates
- mr4461gndec.8246 — Teach-back + log

### Day 19 ⬜
- mr4461gndec.8330 — Recall (10 min)
- mr4461gndec.8347 — Build: invoice workflow
- mr4461gndec.8450 — Test with messy invoices
- mr4461gndec.8540 — Teach-back + log

### Day 20 ⬜
- mr4461gndec.18996 — Recall (10 min)
- mr4461gndec.19013 — Rebuild tracker backup two ways
- mr4461gndec.19110 — Compare agentic vs fixed
- mr4461gndec.19211 — Write tool-neutral blueprints
- mr4461gndec.19338 — Business systems map
- mr4461gndec.19455 — ROI calculator
- mr4461gndec.19822 — Sketch Workflow 2 in Zapier
- mr4461gndec.19896 — Teach-back + log

### Day 21 ⬜
- mr4461gndec.9215 — Recall (10 min)
- mr4461gndec.9251 — Finish rolled-over items
- mr4461gndec.9281 — Rebuild Workflow 1 from scratch
- mr4461gndec.9328 — Tidy your glossary

### Day 22 ⬜
- mr4461gndec.9600 — Recall (10 min)
- mr4461gndec.9617 — The agent loop
- mr4461gndec.9690 — Build: invoice status agent
- mr4461gndec.9793 — Teach-back + log

### Day 23 ⬜
- mr4461gndec.9839 — Recall (10 min)
- mr4461gndec.9856 — What MCP is
- mr4461gndec.9926 — Connect Claude to Drive + Sheets
- mr4461gndec.10028 — Build small MCP server
- mr4461gndec.10122 — Teach-back + log

### Day 24 ⬜
- mr4461gndec.10183 — Recall (10 min)
- mr4461gndec.10219 — Anatomy of a skill
- mr4461gndec.10291 — Build workflow-blueprint skill
- mr4461gndec.10398 — Study /ship-and-watch
- mr4461gndec.10471 — Subagents
- mr4461gndec.10550 — Write your own /ship-and-watch
- mr4461gndec.10662 — Teach-back + log

### Day 25 ⬜
- mr4461gndec.10708 — Recall (10 min)
- mr4461gndec.10725 — Chunking, embeddings, retrieval
- mr4461gndec.10789 — Build: SOP assistant
- mr4461gndec.10883 — Teach-back + log

### Day 26 ⬜
- mr4461gndec.10952 — Recall (10 min)
- mr4461gndec.10969 — Write 20 test questions for SOP assistant
- mr4461gndec.11038 — Score, fix, re-score
- mr4461gndec.11110 — Write 3 agent-or-not rules
- mr4461gndec.11199 — Teach-back + log

### Day 27 ⬜
- mr4461gndec.11259 — Recall (10 min)
- mr4461gndec.11295 — Finish rolled-over items
- mr4461gndec.11325 — Explain agents, MCP, skills, RAG
- mr4461gndec.11385 — Tidy your glossary

### Day 28 ⬜
- mr4461gndec.11698 — Recall (10 min)
- mr4461gndec.11715 — Least privilege
- mr4461gndec.11787 — Human approval before risky actions
- mr4461gndec.11893 — Red-team your own build
- mr4461gndec.12022 — Harden and re-run attack
- mr4461gndec.12076 — Review /ship-and-watch guardrails
- mr4461gndec.12196 — Teach-back + log

### Day 29 ⬜
- mr4461gndec.12258 — Recall (10 min)
- mr4461gndec.12275 — Data types
- mr4461gndec.12359 — AI vendors: data storage
- mr4461gndec.12472 — Canadian law: PIPEDA, PHIPA
- mr4461gndec.12565 — Controls: access, retention, backups
- mr4461gndec.12641 — Write one-page data policy
- mr4461gndec.12754 — Teach-back + log

### Day 30 ⬜
- mr4461gndec.12820 — Recall (10 min)
- mr4461gndec.12856 — What to watch: failed/slow runs, cost, accuracy
- mr4461gndec.12936 — Build: error-alert workflow in n8n
- mr4461gndec.13024 — Write runbook for one workflow
- mr4461gndec.13135 — Add fallback + human fallback to invoice workflow
- mr4461gndec.13277 — Teach-back + log

### Day 31 ⬜
- mr4461gndec.13332 — Recall (10 min)
- mr4461gndec.13349 — Versioning prompts and workflows
- mr4461gndec.13431 — Build: switch classifier model, run evals
- mr4461gndec.13565 — Write 5-step upgrade checklist
- mr4461gndec.13634 — Teach-back + log

### Day 32 ⬜
- mr4461gndec.13686 — Recall (10 min)
- mr4461gndec.13703 — Draw consultancy architecture
- mr4461gndec.13832 — Build: lead intake → blueprint → client report
- mr4461gndec.13947 — Add error alerts + runbook
- mr4461gndec.14010 — Teach-back + log

### Day 33 ⬜
- mr4461gndec.14069 — Recall (10 min)
- mr4461gndec.14105 — Finish rolled-over items
- mr4461gndec.14135 — Explain securing agents, data policy, monitoring
- mr4461gndec.14231 — Tidy your glossary

### Day 34 ⬜
- mr4461gndec.19967 — Recall (10 min)
- mr4461gndec.19984 — Write spec for invoice workflow
- mr4461gndec.20115 — CI basics
- mr4461gndec.20237 — Build: automated check on GitHub repo
- mr4461gndec.20353 — Practice handoff: branch, PR, review
- mr4461gndec.20425 — Write what you own vs head of tech owns
- mr4461gndec.20507 — End-to-end audit
- mr4461gndec.21275 — Teach-back + log

### Day 35 ⬜
- mr4461gndec.15128 — Recall (10 min)
- mr4461gndec.15145 — Write 15-question discovery script
- mr4461gndec.15193 — Mock interview
- mr4461gndec.15265 — Map 3 processes + Opportunity Report
- mr4461gndec.15363 — Teach-back + log

### Day 36 ⬜
- mr4461gndec.15427 — Recall (10 min)
- mr4461gndec.15463 — Change-management basics
- mr4461gndec.15541 — Write staff SOP for invoice workflow
- mr4461gndec.15617 — Run 20-minute training session
- mr4461gndec.15714 — Teach-back + log

### Day 37 ⬜
- mr4461gndec.15789 — Recall (10 min)
- mr4461gndec.15806 — Client-facing runbook
- mr4461gndec.15915 — Maintenance plan
- mr4461gndec.15984 — Write client-facing outage plan
- mr4461gndec.16096 — Scoping basics
- mr4461gndec.16176 — Teach-back + log

### Day 38 ⬜
- mr4461gndec.16227 — Recall (10 min)
- mr4461gndec.16244 — 20-minute demo
- mr4461gndec.16379 — Package 3 case studies

### Day 39 ⬜
- mr4461gndec.16506 — Recall (10 min)
- mr4461gndec.16542 — Finish rolled-over items
- mr4461gndec.16572 — Meet head of tech
- mr4461gndec.16618 — Retrospective
- mr4461gndec.16679 — Plan next phase

---

## Development Notes

- Site repo: `/home/claude/mark-consultant-site`
- Live URL: Deployed on Vercel (check git remote origin)
- Git workflow: Edit files → commit → push → Vercel auto-deploys
