# CTO SYSTEM
**Last Updated:** 2026-04-27
**Version:** 1.0.0
**Owner:** CEO (Direct)
**Managed by:** CTO + Specialist Network

---

## WHAT IS THIS?

This repository is the brain of a living, learning CTO system. The CTO acts as a direct report to the CEO, receiving projects, routing them to specialist teams, and accumulating institutional knowledge over time.

---

## HOW IT WORKS

```
CEO gives project to CTO
         ↓
CTO scans & routes to specialist(s)
         ↓
CTO generates Handoff Prompt
         ↓
CEO loads prompt into specialist session
         ↓
Specialist executes & returns Handoff Report
         ↓
CEO loads report back into CTO
         ↓
CTO updates memory & determines next steps
         ↓
Repeat until project complete
```

---

## DIRECTORY STRUCTURE

```
cto-system/
├── CTO/                               # CTO core files
│   ├── CTO_SYSTEM_PROMPT.md           # Load this to activate the CTO
│   ├── INSTITUTIONAL_MEMORY.md        # Grows smarter over time
│   └── ACTIVE_PROJECTS.md             # Current project register
│
├── specialists/                       # All specialist prompts
│   ├── md-specialist/                 # Markdown & documentation
│   └── github-specialist/             # Version control & repos
│
├── projects/
│   ├── _templates/                    # Handoff prompt & report templates
│   ├── _active/                       # Projects in progress
│   └── _completed/                    # Archived projects
│
├── handoff-reports/                   # All completed reports
└── prompts/                           # Standalone reusable prompts
```

---

## QUICK START — LOADING THE CTO

1. Open a new Claude session
2. Copy the full contents of `CTO/CTO_SYSTEM_PROMPT.md`
3. Also copy `CTO/INSTITUTIONAL_MEMORY.md`
4. Paste both into your first message with: *"You are my CTO. Load your system prompt and institutional memory."*
5. Give the CTO your project

---

## QUICK START — LOADING A SPECIALIST

1. Receive a Handoff Prompt from the CTO
2. Open a new Claude session
3. Paste the Handoff Prompt (it contains everything the specialist needs)
4. The specialist will execute and return a Handoff Report
5. Load the Handoff Report back into your CTO session

---

## CURRENT SPECIALISTS

| ID | Specialist | File |
|----|-----------|------|
| MD | MD Specialist | `specialists/md-specialist/MD_SPECIALIST_PROMPT.md` |
| GH | GitHub Specialist | `specialists/github-specialist/GITHUB_SPECIALIST_PROMPT.md` |
| MANYCHAT | ManyChat Specialist | `specialists/manychat/MANYCHAT_SPECIALIST_PROMPT.md` |
| AIRTABLE | Airtable Specialist | `specialists/airtable/AIRTABLE_SPECIALIST_PROMPT.md` |
| GSHEETS | Google Sheets Specialist | `specialists/google-sheets/GSHEETS_SPECIALIST_PROMPT.md` |
| MAKE | Make Specialist | `specialists/make/MAKE_SPECIALIST_PROMPT.md` |
| SLACK | Slack Specialist | `specialists/slack/SLACK_SPECIALIST_PROMPT.md` |
| INSTAGRAM | Instagram Specialist | `specialists/instagram/INSTAGRAM_SPECIALIST_PROMPT.md` |
| FACEBOOK | Facebook Specialist | `specialists/facebook/FACEBOOK_SPECIALIST_PROMPT.md` |
| GMAIL | Gmail Specialist | `specialists/gmail/GMAIL_SPECIALIST_PROMPT.md` |
| WHATSAPP | WhatsApp Specialist | `specialists/whatsapp/WHATSAPP_SPECIALIST_PROMPT.md` |
| CANVA | Canva Specialist | `specialists/canva/CANVA_SPECIALIST_PROMPT.md` |
| GDRIVE | Google Drive Specialist | `specialists/google-drive/GDRIVE_SPECIALIST_PROMPT.md` |
| GDOCS | Google Docs Specialist | `specialists/google-docs/GDOCS_SPECIALIST_PROMPT.md` |
| STRIPE | Stripe Specialist | `specialists/stripe/STRIPE_SPECIALIST_PROMPT.md` |
| REVOLUT | Revolut Specialist | `specialists/revolut/REVOLUT_SPECIALIST_PROMPT.md` |
| CHATGPT | ChatGPT Specialist | `specialists/chatgpt/CHATGPT_SPECIALIST_PROMPT.md` |
| CLAUDE-SPECIALIST | Claude Specialist | `specialists/claude/CLAUDE_SPECIALIST_PROMPT.md` |
| PERPLEXITY | Perplexity Specialist | `specialists/perplexity/PERPLEXITY_SPECIALIST_PROMPT.md` |

---

## ADDING NEW SPECIALISTS

1. Tell the CTO: *"I need a specialist for [X]"*
2. CTO will generate a handoff prompt for the MD Specialist
3. MD Specialist will create the new specialist prompt file
4. GitHub Specialist will commit it to the repo
5. CTO will update the specialist table in this README

---

## SYSTEM RULES

- Every `.md` file must be timestamped with `Last Updated: YYYY-MM-DD`
- All specialist prompts must be researched before being written (no stale info)
- Every project starts with a Handoff Prompt and ends with a Handoff Report
- Handoff Reports are always loaded back into the CTO to build institutional memory
- No sensitive data (API keys, passwords) ever committed to this repo
