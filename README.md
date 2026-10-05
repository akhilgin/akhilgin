# Hi, I'm Akhil 👋

**GTM Engineer · GTM Operations · Marketing Ops · RevOps · India (open to remote)**

I build the systems behind B2B revenue teams: CRM automation, attribution, enrichment, and AI agents that take manual work off marketing and sales.

[![Email](https://img.shields.io/badge/Email-akhil@akhilg.info-D14836?style=flat&logo=gmail&logoColor=white)](mailto:akhil@akhilg.info)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Akhil%20G-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/akhilgvithura/)

---

## About Me

I have 8+ years of experience across demand generation, marketing operations, and GTM engineering. My work sits between marketing, engineering, and revenue operations. I write the Python, webhooks, and AI workflows that connect Salesforce, ad platforms, GA4, enrichment tools, and Slack, so GTM teams get clean data and fast answers without filing a ticket.

Since 2021 I've been at **Inflection.io** (B2B SaaS), where I own GTM ops, Salesforce administration, paid acquisition, and internal AI tooling. Some of the work:

- **Demo Intelligence Agent:** enriches every inbound demo request with ICP fit, account context, and ownership, then posts it to Slack. AE research went from about 30 minutes per lead to a few seconds.
- **AI weekly GTM reporting:** combines Salesforce, GA4, LinkedIn Ads, Slack, and Notion into an executive summary, replacing manual reporting.
- **Salesforce at scale:** imported 3,919 target accounts through API automation instead of Data Loader, and enriched 2,498 accounts.
- **Paid acquisition:** cut LinkedIn CPL from $380 to $37.50 by redesigning audiences and using manual bidding. Traced an 88% account-wide drop in LinkedIn delivery to a device-exclusion setting.
- **Event ops:** ran GTM operations for a 655-registration B2B conference with 50%+ year-over-year registration growth.

Before that, I led business operations and digital marketing at Marrina Decisions (an Adobe partner), marketing and SEO at TutorComp, and a 17-person marketing team at Bytekat Technologies.

LinkedIn Certified Insider · Google Hall of Fame (Vulnerability Reward Program)

---

## Tech Stack

![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat&logo=anthropic&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat&logo=n8n&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat&logo=salesforce&logoColor=white)
![HubSpot](https://img.shields.io/badge/HubSpot-FF7A59?style=flat&logo=hubspot&logoColor=white)
![Google Analytics](https://img.shields.io/badge/GA4-E37400?style=flat&logo=googleanalytics&logoColor=white)
![Google Tag Manager](https://img.shields.io/badge/Tag%20Manager-246FDB?style=flat&logo=googletagmanager&logoColor=white)
![LinkedIn Ads](https://img.shields.io/badge/LinkedIn%20Ads-0A66C2?style=flat&logo=linkedin&logoColor=white)
![Slack](https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white)
![Zapier](https://img.shields.io/badge/Zapier-FF4F00?style=flat&logo=zapier&logoColor=white)

**AI & Automation:** Claude Code, AI agents, MCP servers, n8n, Zapier, webhooks, REST APIs, headless browser automation, launchd
**CRM & Revenue Systems:** Salesforce (admin, Flows, API), HubSpot, Marketo, RevenueHero
**Enrichment & Data:** Apollo, Clay, Keyplay, BuiltWith, NeverBounce
**Paid Acquisition:** LinkedIn Ads, Google Ads, Meta Ads, Reddit Ads, OpenAI Ads
**Analytics:** GA4, Google Tag Manager, Amplitude, Mixpanel, Segment

---

## Featured Projects

### [Demo Request Intel Agent](https://github.com/akhilgin/demo-request-intel-agent)
> When a target account fills out the demo form, this posts a short brief to Slack: who they are, account fit, the owner, any open opportunity, and how they found you. AE research drops from about 30 minutes to a few seconds. It reads from the CRM, filters out freemail, internal and non-target domains, and uses deterministic dedup so nothing posts twice. An optional LLM writes the summary from structured facts.

`Python` `Salesforce` `Slack` `Claude API` `launchd`

---

### [Salesforce Data Quality Monitor](https://github.com/akhilgin/salesforce-data-quality-monitor)
> A read-only daily health check for Salesforce. It runs SOQL checks (duplicates, junk titles, placeholder names, email/account domain mismatches, past-due opportunities), compares each run to the last, and posts a RED/YELLOW/GREEN summary to Slack. Known backlogs alert only when they grow, so the alerts stay useful.

`Python` `Salesforce` `SOQL` `Slack` `launchd`

---

### [Apollo Job-Change Sync](https://github.com/akhilgin/apollo-job-change-sync)
> Handles job changes the right way. It flags the old contact instead of overwriting it, finds the person's new work email through Apollo, accepts it only if it matches the new company's domain, and creates a fresh contact and account in Salesforce. Runs as a dry run by default, takes backups before writing, and never creates a contact without an email.

`Python` `Apollo` `Salesforce` `Composite API` `Data Hygiene`

---

### [Event Registration → GA4 Attribution](https://github.com/akhilgin/event-registration-ga4-attribution)
> Connects Luma event registrations back to the ads and content that drove them. A small embed script carries the GA4 client ID through registration, and a webhook handler sends the event to GA4 through the Measurement Protocol, giving first-touch, last-touch, and full-path attribution for event signups. Includes the mistakes that break it silently.

`GA4` `Measurement Protocol` `Luma` `Zapier` `JavaScript` `Python`

---

### More projects

| Project | What it does | Stack |
|---|---|---|
| [Salesforce Pipeline Attribution](https://github.com/akhilgin/salesforce-pipeline-attribution) | Multi-touch campaign and channel attribution (first, last, linear, U-shaped) plus a static HTML pipeline dashboard | Python, Salesforce |
| [Fathom → Salesforce Contact Roles](https://github.com/akhilgin/fathom-salesforce-contact-roles) | Turns call attendees into Opportunity Contact Roles; unknown attendees go to a review list, never auto-created | Python, Fathom API, Salesforce |
| [Slack Account Intel Bot](https://github.com/akhilgin/slack-account-intel-bot) | Account intel dropped in Slack gets matched to the right account and logged as a Salesforce Task, with an AI-maintained digest | Python, Slack API, Salesforce, Claude API |
| [Marketing Analytics Scripts](https://github.com/akhilgin/marketing-analytics-scripts) | GA4 paid, organic, AI-assistant-ads, email-launch and 404 reports; Meta Ads daily report; Tag Manager audit CLI | Python, GA4 Data API, Meta Marketing API, GTM API |
| [Claude Code GTM Workspace](https://github.com/akhilgin/claude-code-gtm-workspace) | Template for running GTM ops through Claude Code: CLAUDE.md working rules, slash commands, Keychain secrets, scheduled runs | Claude Code, MCP, Python, launchd |

---

## Get in Touch

Happy to talk GTM engineering, Salesforce architecture, attribution, or practical AI automation for revenue teams.

📬 akhil@akhilg.info · 💼 [LinkedIn](https://www.linkedin.com/in/akhilgvithura/)
