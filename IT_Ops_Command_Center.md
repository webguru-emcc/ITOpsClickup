# IT Operations – Command Center Reference
*Last Updated: May 26, 2026*

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
**Workspace:** Ezra McClendon's Workspace
**Top-Level Page:** 🖥️ IT Operations
**IT Operations Page ID:** 36c27749-5702-81be-8aad-ed521db72fcb

| Section | Databases |
|---------|-----------|
| Infrastructure Operations | Active Projects, Tickets & Changes |
| Windows Team | Active Projects, Tickets & Changes |
| Linux Team | Active Projects, Tickets & Changes |
| 📋 PTO Tracker *(shared, top-level)* | PTO Tracker |
| ✅ To Do List | To Do List |
| 📊 IT Ops Dashboard | Linked views of all databases |

### Key Data Source IDs
| Database | Data Source ID |
|----------|---------------|
| Infra Ops – Active Projects | 731fb08d-31d7-49c8-95eb-41a069995226 |
| Infra Ops – Tickets & Changes | 5f90e886-2d98-48ac-a96c-e451079fff56 |
| Windows – Active Projects | 52439179-83bf-4baf-9f20-66f8cbab1140 |
| Windows – Tickets & Changes | cc3a315a-82df-49a1-95eb-307fa1e12c92 |
| Linux – Active Projects | 98e9b7d5-c80f-4fad-8fdb-640ca456fb72 |
| Linux – Tickets & Changes | 4fa81853-30f8-4bfb-ae59-88f248365e68 |
| PTO Tracker | 75e2ac81-f902-4691-b37e-048183e9944f |
| To Do List | 9b9f85a5-34ab-446c-bba0-0e82b3632b2c |

### Database Fields
**Active Projects:** Name, Team, Team Member, Status, Priority, Due Date, Notes
**Tickets & Changes:** Name, Team, Team Member, Type (Ticket/Change), Status, Priority, Due Date, Notes
**PTO Tracker:** Name, Team Member, Team, Start Date, End Date, Notes
**To Do List:** Task, Status, Priority, Due Date, Notes

### Team Member Dropdowns
- **Infrastructure Operations:** Kyle, Reema, Maurice, Isaac, Ezra, Imran
- **Windows Team:** Joe, Taylor, Eric
- **Linux Team:** Wasim, Julian, Venkat, Lonnie
- **PTO Tracker:** All 12 members + Team field

---

## 📊 IT Ops Dashboard

**URL:** https://www.notion.so/36c27749570281bfa123ca202a2e8b9d

Contains 3 live views (auto-filtered, real-time):
- 📋 **All Open Projects** — grouped by Team, sorted by Due Date
- 🎫 **All Open Tickets & Changes** — grouped by Team, sorted by Priority
- 🏖️ **Open PTO** — sorted by Start Date

---

## 🏖️ PTO Tracker

**Data Source ID:** 75e2ac81-f902-4691-b37e-048183e9944f

### Naming Convention
```
PTO – [First Name] | [Month Day–Day]
```
**Due Date:** Set to the **first day** of PTO

### Current PTO Entries
| Name | Team | Start | End |
|------|------|-------|-----|
| Reema | Infrastructure Operations | Jun 25, 2026 | Jun 29, 2026 |
| Reema | Infrastructure Operations | Jul 22, 2026 | Jul 27, 2026 |
| Eric | Windows Team | May 26, 2026 | Jun 3, 2026 |

---

## ✅ To Do List

**Data Source ID:** 9b9f85a5-34ab-446c-bba0-0e82b3632b2c

### Current Items
| Task | Status | Priority | Due Date |
|------|--------|----------|----------|
| Confirm if Agent 2 is working in SkippyAI | Not Started | Normal | — |

---

## 📅 Calendar Setup

**Primary Calendar:** EzraMcC
**Calendar ID:** E7B236E6-CB1E-4DB0-B4B7-ED3C58D51FDA

> All events created by Claude go into EzraMcC.

### Recurring Events
| Event | Schedule | Notes |
|-------|----------|-------|
| 🏖️ Weekly PTO Check – Who's Out This Week? | Every Monday at 8:00 AM | Check Notion PTO Tracker |

---

## 🔗 Tools & Integrations

| Tool | Status | Purpose |
|------|--------|---------|
| Notion | ✅ Connected | Projects, Tickets, PTO, To Do tracking |
| ClickUp (IT Ops) | ⚠️ Deprecated | Replaced by Notion |
| GitHub | ✅ Connected | Hosts this .md file |
| EzraMcC Calendar | ✅ Active | All calendar events |
| Make (Integromat) | ✅ Active | Daily email digest of open projects |

**GitHub Repo:** [github.com/webguru-emcc/ITOpsProjects](https://github.com/webguru-emcc/ITOpsProjects)

### Make Scenario (Daily Email Digest)
- Queries Infra Ops, Windows, Linux Active Projects for non-completed items
- Sends daily email to ezramcc@gmail.com with link to Notion dashboard
- **Pending fix:** Duplicate email issue + dynamic project listing in email body

---

## 📋 Active Projects

| Project | Team Member | Team | Due Date | Status |
|---------|-------------|------|----------|--------|
| Install DevOps Servers in Prod Tenant | Reema | Infrastructure Operations | May 29, 2026 | Not Started |
| Deploy Skippy AI Servers in Prod Tenant | Kyle | Infrastructure Operations | May 29, 2026 | Not Started |

---

## 📋 Pending / To-Do

- [ ] **Fix Make scenario** — duplicate email issue + pull live project data into email body
- [ ] **Review Zoho Projects vs Notion** (reminder set for today noon)
- [ ] **Delete old default Notion pages** (Getting Started, To Do List default pages)
- [ ] **Create Monday 8AM recurring PTO calendar reminder** (pointing to Notion)

---

## 🔄 How to Resume Context in a New Chat

If you ever need to start a new chat, paste this entire .md file at the top of the conversation and say:

> *"You are Ezra, Director of IT Operations. Here is our reference doc — pick up where we left off."*

**What persists without the .md (saved to Claude memory):**
- EzraMcC calendar preference
- Team rosters and structure
- Notion workspace IDs and data source IDs
- GitHub repo and dashboard URL
- PTO naming convention

**What requires the .md to restore:**
- Full database field details
- Active project list
- Make scenario details
- Pending to-dos

---

## 🔧 Notes & Conventions

- Use this chat as the ongoing IT Ops command center
- Notion is the primary tracking tool — team members tracked via dropdown (no accounts needed)
- Always set Team field when creating projects/tickets so dashboard grouping works correctly
- GitHub token: stored privately — do not commit to repo. Paste into chat when needed.
- Voice input: use device dictation (iOS mic on keyboard, Mac Dictation) to speak into this chat
