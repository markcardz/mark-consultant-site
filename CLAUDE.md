# Claude Project Instructions for AI Consultant Training

## Auto-Tracker Updates

**When to trigger:** After Mark completes ALL tasks in a day's checklist (typically after "Teach-back + log" or when he confirms the day is done).

**What to do:**
1. Read the AI Consultant Training Progress Log tracker (artifact ID: 382634af-1748-4b02-9f8a-6b4130ab6244)
2. Identify the Day N section with incomplete tasks
3. Use Claude Docs `update` tool with `set` operations to mark each task's listItem as `checked='true'`
4. Use full session ID prefix from the read result (currently: `mh8tdvfw9bk`) when constructing block IDs
5. Apply all checks in a single atomic update call
6. Confirm completion to Mark in 1-2 sentences

**Implementation pattern:**
```
container: {"kind": "project", "id": "382634af-1748-4b02-9f8a-6b4130ab6244"}
ref: {"object": "node", "id": "6df7702a-2cb3"}
ops: [
  {"op": "set", "target": {"kind": "blocks", "ids": ["<session>.<clock>"]}, "attrs": {"checked": true}}
  ... one op per task
]
```

**Mark's learning goals:** Understand the full workflow (build → git → deploy), and eventually explain this to clients. Automatic tracker updates keep the learning record accurate without manual overhead.

## Development Notes

- Site repo: `/home/claude/markcardz/mark-consultant-site`
- Live URL: Deployed on Vercel (check git remote origin)
- Git workflow: Edit files → commit → push → Vercel auto-deploys
- Use device bridge tools to edit Mark's local files directly (don't edit in cloud container)
