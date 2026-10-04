# FLOW VELLO — AGENCY COMMAND CENTER

## Purpose

This is the operational control room for the three-person agency.

Use **one shared workspace** instead of scattered WhatsApp chats, spreadsheets, notes, GitHub issues, and memory.

Recommended starting platform: **Notion**.

Do not build a custom SaaS for ourselves yet. That would be another engineering procrastination project.

The Command Center should contain:

1. Company Dashboard
2. Leads / CRM
3. Opportunities
4. Clients
5. Projects
6. Tasks
7. Sales Activity
8. Delivery / QA
9. Offers
10. Proof / Case Studies
11. SOPs
12. Finance
13. Meeting notes
14. Weekly scoreboard

## Access

All three members have access.

Permissions should follow ownership:

- A: full control of CRM, sales pipeline, commercial records
- B: full control of delivery/project records
- C: full control of QA, proof, systems
- All three: read access to company dashboard and relevant project data

Sensitive finance/admin data can be restricted if needed.

## HOME DASHBOARD

The home page should show only what the team needs today:

### TODAY

- My tasks
- Overdue tasks
- Today's calls
- New trigger accounts
- Follow-ups due
- Active opportunities
- Active client milestones
- QA blockers
- Cash collected this month

### COMPANY SCOREBOARD

- trigger accounts reviewed
- qualified accounts
- first contacts
- follow-ups
- replies
- qualified calls
- proposals
- deposits
- active projects
- shipped milestones
- QA pass rate
- blocked tasks >24h

## DATABASES

### 1. LEADS

Fields:

- Company
- Website
- Industry
- Location
- Signal
- Signal score
- Evidence
- Buyer
- Buyer role
- Offer
- Owner
- Status
- First contact
- Last contact
- Next action
- Source

Statuses:

Signal Found → Verified → Buyer Identified → Contacted → Replied → Qualified → Nurture → Lost

### 2. OPPORTUNITIES

Fields:

- Company
- Buyer
- Problem
- Offer
- Estimated value
- Stage
- Probability
- Next action
- DRI
- Technical risk
- Proposal
- Deposit
- Lost reason

Stages:

Qualified → Discovery → Scope → Proposal → Negotiation → Won → Lost

### 3. PROJECTS

Fields:

- Client
- Offer
- DRI
- Start date
- Deadline
- Scope
- Acceptance criteria
- Milestones
- Status
- Risk
- Payment status
- QA status
- Demo date
- Handoff date

Statuses:

Onboarding → Build → QA → Demo → Handoff → Complete

### 4. TASKS

Every task has:

- Task
- DRI
- Project/Opportunity
- Priority
- Due date
- Status
- Definition of Done
- Blocker

Statuses:

Backlog → Today → Doing → Review → Done → Blocked

### 5. PROOF

Store only real evidence:

- client
- problem
- work
- before
- after
- measurable result
- permission status
- screenshot/demo
- case-study status

No invented numbers.

## PERSONAL WORK VIEWS

### A VIEW — REVENUE COMMAND

Show:

- today's prospecting
- hot accounts
- follow-ups due
- replies
- calls
- proposals
- negotiations
- cash
- lost reasons

A should not need to open technical task boards to know what needs selling.

### B VIEW — DELIVERY COMMAND

Show:

- active projects
- today's milestones
- blockers
- technical risks
- deployments
- integrations
- tasks awaiting review

B should not spend the day looking through sales noise.

### C VIEW — QA + SYSTEMS COMMAND

Show:

- QA queue
- bugs
- release checks
- proof assets
- demos
- documentation
- reusable components
- process improvements

## PROJECT RULE

Every project has exactly one DRI.

A:
commercial/client DRI

B:
technical delivery DRI

C:
QA/release DRI

Do not create three owners for one outcome.

## DAILY FLOW

08:30
All three open Command Center.

08:30–08:45
Stand-up from dashboard.

08:45–11:00
A hunts signals and sells.
B builds.
C QA/proof/systems.

11:00
Qualified opportunity → technical review if required.

17:00
Everyone updates status.

17:20
Everyone creates tomorrow's first task.

If it is not in the Command Center, it is not considered committed work.

## WEEKLY REVIEW

Every week answer:

1. How many real buying signals did we find?
2. Which source produced the best conversations?
3. Which signal produced the best opportunities?
4. Which offer got the most demand?
5. Where did prospects disappear?
6. Why were proposals lost?
7. What delivery bottleneck repeated?
8. What should be automated?
9. What should be deleted?
10. What is next week's one commercial experiment?

## TOOL RULE

Start with **Notion + GitHub + existing communication tools**.

Do not build a custom agency dashboard until the team has proven the workflow and can name the exact recurring pain the custom software would solve.

The agency's job is to build client systems.

It should not spend its first revenue building an internal CRM that existing tools already handle.

## THE GOLDEN RULE

The Command Center is not another documentation project.

Open it every morning.

Update it every day.

Make decisions from it.

If the team creates the dashboard and then returns to WhatsApp messages, private notes, and memory, the system has failed.
