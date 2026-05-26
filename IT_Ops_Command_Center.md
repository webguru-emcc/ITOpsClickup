# IT Operations – Command Center Reference
*Last Updated: May 25, 2026*

---

## 👤 Director
**Ezra** – Director of IT Operations

---

## 👥 Teams

### Infrastructure Operations
Kyle, Reema, Maurice, Isaac, Ezra, Imran

### Windows Team
Joe, Taylor, Eric

### Linux Team
Wasim, Julian, Venkat, Lonnie

---

## 🗂️ Notion Workspace Structure

**Primary Tool:** Notion (free plan)
**Top-Level Page:** 🖥️ IT Operations

| Section | Databases |
|---------|-----------|
| Infrastructure Operations | Active Projects, Tickets & Changes |
| Windows Team | Active Projects, Tickets & Changes |
| Linux Team | Active Projects, Tickets & Changes |
| 📋 PTO Tracker *(shared, top-level)* | PTO Tracker |

### Database Fields
**Active Projects:** Name, Team Member, Status, Priority, Due Date, Notes
**Tickets & Changes:** Name, Team Member, Status, Priority, Type (Ticket/Change), Due Date, Notes
**PTO Tracker:** Name, Team Member, Team, Start Date, End Date, Notes

### Team Member Dropdowns
- **Infrastructure Operations:** Kyle, Reema, Maurice, Isaac, Ezra, Imran
- **Windows Team:** Joe, Taylor, Eric
- **Linux Team:** Wasim, Julian, Venkat, Lonnie
- **PTO Tracker:** All 12 members + Team field

---

## 🏖️ PTO Tracker

**Notion Page:** 📋 PTO Tracker
**Data Source ID:** 75e2ac81-f902-4691-b37e-048183e9944f

### Naming Convention
```
PTO – [First Name] | [Month Day–Day]
```

### Current PTO Entries
| Name | Team | Start | End |
|------|------|-------|-----|
| Reema | Infrastructure Operations | Jun 25, 2026 | Jun 29, 2026 |
| Reema | Infrastructure Operations | Jul 22, 2026 | Jul 27, 2026 |
| Eric | Windows Team | May 26, 2026 | Jun 3, 2026 |

---

## 📅 Calendar Setup

**Primary Calendar:** EzraMcC
**Calendar ID:** E7B236E6-CB1E-4DB0-B4B7-ED3C58D51FDA

> All events created by Claude go into EzraMcC.

### Recurring Events
| Event | Schedule | Notes |
|-------|----------|-------|
| 🏖️ Weekly PTO Check – Who's Out This Week? | Every Monday at 8:00 AM | Check Notion PTO Tracker |
| 📬 Review Notion Email Notifications Setup | Tue May 26 at 10:00 AM | One-time; 10 min reminder |

---

## 🔗 Tools & Integrations

| Tool | Status | Purpose |
|------|--------|---------|
| Notion | ✅ Connected | Projects, Tickets, PTO tracking |
| ClickUp (IT Ops workspace) | ⚠️ Deprecated | Replaced by Notion |
| ClickUp (IT Operations workspace) | ⚠️ Deprecated | Original workspace |
| GitHub | ✅ Connected | Hosts this .md file |
| EzraMcC Calendar | ✅ Active | All calendar events |

**GitHub Repo:** [github.com/webguru-emcc/ITOpsProjects](https://github.com/webguru-emcc/ITOpsProjects)

---

## 📋 Pending / To-Do

- [ ] **Review Notion email notifications** (scheduled Tue May 26, 10 AM)
  - Goal: enable real-time email alerts for key events (new entries, status changes)
- [ ] **Delete old ClickUp workspaces** (IT Operations + IT Ops) — no longer needed

---

## 🔄 How to Resume Context in a New Chat

If you ever need to start a new chat, paste this entire .md file at the top of the conversation and say:

> *"You are Ezra, Director of IT Operations. Here is our reference doc — pick up where we left off."*

Claude will have full context on the team, Notion structure, PTO conventions, and calendar setup immediately.

**What persists without the .md:**
- Notion databases and entries (always saved)
- Calendar events in EzraMcC (always saved)
- EzraMcC calendar preference (saved in Claude memory)

**What requires the .md to restore:**
- Team roster and structure
- Notion data source IDs and conventions
- PTO naming rules
- Any ongoing projects or to-dos

---

## 🔧 Notes & Conventions

- Use this chat as the ongoing IT Ops command center — no need to start a new chat for each task
- Notion is the primary project/ticket/PTO tracking tool (free plan, no email invites needed for team members)
- Team members are tracked via dropdown fields — no ClickUp/Notion accounts required for the team
- Voice input: use device dictation (iOS mic on keyboard, Mac Dictation) to speak into this chat
- GitHub token: stored privately — do not commit to repo. Paste into chat when needed.
