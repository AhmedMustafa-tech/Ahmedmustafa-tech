<p align="center">
  <img src="./banner.svg" alt="Ahmed Mohamed, IT Operations & Automation Engineer" width="100%">
</p>

<p align="center">
  <a href="https://AhmedMustafa-tech.github.io/portfolio/"><img src="https://img.shields.io/badge/Portfolio-111111?style=flat-square" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/ahmed-mohamed-9411311a8/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:ahmeedmustafaaa@gmail.com"><img src="https://img.shields.io/badge/Email-444444?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>

## About

I run IT operations across two regional service desks and design the systems behind them: identity and access controls, security rollouts, AI-assisted SLA monitoring and live leadership reporting. I designed, built and maintain every automation shown below.

6+ years in IT support and operations · CCNA · MCSA · Based in Cairo, Egypt · Available for freelance and contract work.

## Impact at a glance

| **14 → 0** | **1× → 24×** | **0** | **3** |
|:-:|:-:|:-:|:-:|
| manual offboarding steps | leadership reporting: once a month → 24 times a day | permanent lockouts in a company-wide MFA rollout | legal entities covered by that rollout |

## Selected work

### Company-wide device MFA rollout
`Security` `JumpCloud` `macOS` `Windows` `Change management`

Planned and led MFA enforcement on every company laptop across three legal entities, in response to a regulatory audit observation.
- Designed a six-phase rollout: assessment, IT pilot, user pilot, staged waves, executives, verification
- Identified two lockout patterns mid-rollout and built the reset and credential-recovery procedures for both
- Escalated an enforcement gap and a Windows biometric conflict to the vendor with evidence
- **Result:** full coverage on macOS and Windows with **zero permanent lockouts**

### AI-assisted SLA monitoring for two service desks
`n8n` `Jira REST API` `OpenAI GPT` `Slack API`

Designed and built an AI assistant that watches SLA risk across two regional Jira Service Management queues.
- Notifies the assignee before a ticket breaches and escalates stalled tickets automatically
- Answers queue questions in plain language and returns approved procedures, with deterministic output guardrails
- **Result:** SLA follow-up moved from manual queue checks to continuous, scheduled monitoring

### Zero-touch employee offboarding
`Identity & access` `JumpCloud` `Google Workspace` `Jira` `Slack` `MDM`

Automated the full leaver process across five systems, with an audit record written to the ticket on every run.
- Removes directory, SSO, Google Workspace, Jira and Slack access at 18:00 on the last working day
- Leaves people only two physical confirmations: laptop returned, internal tools deactivated
- **Result:** **14 manual steps → 0**, with same-day access removal

### Executive IT dashboard
`Data pipeline` `Jira REST API` `n8n` `React`

Built a live reporting pipeline from Jira to a leadership dashboard, refreshed hourly.
- Resolved a production out-of-memory failure by refactoring the pipeline into per-batch sub-workflows
- **Result:** reporting went from **1× a month to 24× a day**, expanded from one region to two

### P0 email blocklisting incident
`Incident response` `BigQuery` `DNS` `SPF · DKIM · DMARC`

Coordinated the response when the corporate domain was blocklisted, across security, platform owners and business teams.
- Ran a domain-wide sender audit in BigQuery that identified the dominant bulk sender
- Moved bulk mail onto dedicated, authenticated subdomains; traced a follow-on reply-bounce issue to missing MX records and fixed it
- **Result:** bulk sending isolated from the corporate domain; root cause analysis delivered

Full case studies: **[ahmedmustafa-tech.github.io/portfolio](https://AhmedMustafa-tech.github.io/portfolio/)**

## Services

| Service | Scope |
|:--|:--|
| **Workflow automation** | n8n workflows integrating Jira, Slack, Google Workspace, Notion and REST APIs |
| **SLA monitoring** | Proactive alerts on at-risk tickets and automated escalation |
| **User lifecycle** | Automated onboarding and offboarding across directory, SSO and SaaS, with an audit trail |
| **Reporting & dashboards** | Live ITSM dashboards and scheduled reports for leadership |
| **Jira Service Management** | Queue design, JQL, SLA configuration and reporting |
| **AI assistants for IT** | Internal assistants that answer queue and procedure questions using OpenAI GPT |

## Approach

1. **Discovery** — Document the current process, systems, owners and failure points.
2. **Build** — Develop against test or read-only access; no production changes before sign-off.
3. **Validate** — Test end to end with real scenarios and confirm the output with stakeholders.
4. **Handover** — Documentation and a runbook so your team can operate it independently.

## Technical skills

**ITSM:** Jira Service Management, JQL, SLA management  
**Automation:** n8n, REST APIs, JavaScript, PowerShell, OpenAI API  
**Identity & access:** JumpCloud, Google Workspace, Active Directory, SSO, MFA  
**Data & reporting:** BigQuery, Google Sheets API  
