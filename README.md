# Agentic Design Skills

Two Claude skills for designers — a **Product Agent** and a **Design Agent** — that turn a raw brief into structured design directions ready to build from.

Built for the JDP × Flight Centre Capability Day.

---

## Skills

### Product Agent
Acts as a senior PM. Give it a brief or problem statement and it returns a structured **Problem Framing** with User Need, Constraints, Success Criteria, Root Cause, and a Primary Opportunity.

### Design Agent
Acts as a senior UX designer. Give it the Product Agent output and it proposes **2–3 distinct design directions**, each with a Design Bet, interaction patterns, and honest trade-offs. You choose one and take it into AI Studio to build.

---

## Installation

1. **Download** this repo as a ZIP — click the green **Code** button → **Download ZIP**
2. Unzip it — you'll find two folders: `product-agent` and `design-agent`
3. Open **Claude Desktop** and click the folder icon to select a workspace folder
4. Inside your workspace folder, create this structure:
   ```
   workspace/
   └── .claude/
       └── skills/
           ├── product-agent/
           │   └── SKILL.md
           └── design-agent/
               └── SKILL.md
   ```
5. Drop the two folders into `.claude/skills/`
6. **Restart Claude Desktop** — the skills will appear automatically

---

## Usage

Run them in order:

**Step 1 — Product Agent**
```
Run the product agent.

[paste your brief or problem here]
```

**Step 2 — Design Agent**
```
Run the design agent.

[paste the Product Agent output here]
```

Review the 2–3 directions, choose one, then take it into Google AI Studio or Claude Design to build.

---

## Download link

Share this URL to give others a direct ZIP download:

```
https://github.com/taliayat-fc/agentic-design-skills/archive/refs/heads/main.zip
```
