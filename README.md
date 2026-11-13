# Awesome-Customer-Support-Helpdesk-Software [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Curated list of customer support software, open-source helpdesk systems, ticketing platforms, and shared customer service inboxes.

A comprehensive ecosystem overview tracking leading commercial **SaaS platforms** and **open-source GitHub projects** for **Customer Support & Helpdesk Software**. This collection covers ticket management, omnichannel messaging, AI service agents, ITIL service desks, and self-hosted shared customer service inboxes.

---

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Feature Matrix & Selection Guide](#feature-matrix--selection-guide)
- [How to Contribute](#how-to-contribute)
- [Disclaimer & Evaluation Notes](#disclaimer--evaluation-notes)

---

## Sector Overview & Market Dynamics

The global customer support and help desk software market is valued at approximately **$11B – $15.6B** (projected to reach over **$25B – $38B** by the mid-2030s at an 8–10% CAGR, with the customer self-service and conversational AI sub-segment expanding even faster at ~20% CAGR). 

The sector is **moderately fragmented**: while enterprise mega-vendors like ServiceNow, Salesforce, Atlassian, and Zendesk command significant market share at the top tier, there is no single "winner-take-all" monopoly. Instead, the market is characterized by strong verticalized sub-markets—ranging from e-commerce specialist desks (Gorgias) and collaborative team email inboxes (Front, Help Scout) to developer-centric ITSM tools (Jira Service Management) and a vibrant ecosystem of self-hosted, open-source platforms (Chatwoot, Zammad, FreeScout) catering to privacy, compliance, and cost-conscious operators.

---

## SaaS / Hosted Platforms

Below is a comparison of leading commercial customer support and helpdesk platforms, sorted in descending order by enterprise scale (company market capitalization, acquisition valuation, or ARR run-rate).

| Product | Scale (Valuation / Revenue) | Description | Pricing (Starting Tier) | Free Tier / Trial Limits |
|:---|:---|:---|:---|:---|
| **[ServiceNow CSM](https://www.servicenow.com/)** | **~$105B–$165B Market Cap** ($15.4B TTM Revenue) | Enterprise-grade digital workflow and customer service management connecting front, middle, and back-office operations. | **$130–$150/agent/month** (Standard fulfiller seat, annual contract) | **No permanent free tier**; custom guided enterprise sandbox/demo via sales. |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | **~$38.5B Market Cap** (Atlassian) | Comprehensive IT service management and customer support platform tightly integrated with Jira and Atlassian developer tools. | **$17.65/agent/month** (Standard plan; Premium at $55.28/agent/month) | **Forever Free Tier**: up to **3 agents**, unlimited customers, 2 GB file storage, and 100 emails/day. |
| **[Zendesk Support](https://www.zendesk.com/)** | **$10.2B Buyout Valuation** (~$1.7B ARR) | Industry-standard ticketing system with mature omnichannel queues, SLA routing, and a massive integration marketplace. | **$19/agent/month** (Support Team, annual billing; Suite starts at $55/agent/month) | **14-day free trial** with full access to Suite Professional features; no credit card required. |
| **[Intercom](https://www.intercom.com/)** | **$3.6B Valuation** (Acquired by Salesforce; $400M+ ARR) | AI-first customer service platform featuring the Fin autonomous resolution bot alongside live chat and omnichannel queues. | **$29/seat/month** (Essential plan, annual billing; Fin AI resolutions billed separately at $0.99/outcome) | **14-day free trial** of Essential/Advanced features; no permanent free tier. |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | **~$3.1B Market Cap** (Freshworks, ~$700M+ ARR) | Cloud helpdesk featuring Freddy AI copilot, multi-channel ticket unification, and collaborative team triage. | **$19/agent/month** (Growth plan, annual billing; Pro at $55/agent/month) | **Forever Free Tier**: up to **2 agents**, basic ticket management and knowledge base; also offers a **14-day free trial** of Enterprise. |
| **[Front](https://front.com/)** | **$1.7B Valuation** (~$100M ARR) | Customer communication hub unifying email, SMS, and WhatsApp into shared collaborative team inboxes. | **$19/seat/month** (Starter plan, annual billing, up to 10 seats; Growth at $59/seat/month) | **14-day free trial** of Growth features; no permanent free tier. |
| **[Gorgias](https://www.gorgias.com/)** | **$530M Valuation** (~$60M–$80M ARR) | E-commerce-specialized helpdesk tightly synced with Shopify, BigCommerce, and Magento order management and tracking. | **$40/month** (Starter tier including 50 tickets and 30 automated interactions/month; Basic at $90/month) | **7-day free trial** with access to all standard core features; no credit card required. |
| **[Help Scout](https://www.helpscout.com/)** | **~$150M–$300M Est. Value** (~$30M ARR) | Designed for high-touch customer relationships with shared email mailboxes, live chat, and customer portal docs. | **$25/user/month** (Standard plan, annual billing; Plus at $50/user/month) | **15-day free trial**; also offers a **Forever Free tier** limited to **5 users**, 1 mailbox, and 1 Docs site. |
| **[Deskpro](https://www.deskpro.com/)** | **$25M Series A** (~$10M ARR) | Flexible, feature-dense omnichannel helpdesk platform offering both managed cloud hosting and on-premise deployments. | **$39/agent/month** (Team plan, annual billing, typically min. 5 agents) | **14-day free trial** for both Cloud and On-Premise deployments; no credit card required. |
| **[LiveAgent](https://www.liveagent.com/)** | **Bootstrapped / Profitable** (~$7M–$20M ARR) | Real-time omnichannel help desk software featuring live chat, ticketing, cloud call center, and social integration. | **$15/agent/month** (Small business/Starter tier, annual billing; Medium at $29/agent/month) | **Forever Free Tier**: limited to **1 agent**, 1 email account, 1 chat button, and 7-day ticket history; plus a **30-day free trial** of all premium features. |

---

## Open-Source GitHub Projects

Self-hosted ticketing systems, open-source helpdesks, and community-driven shared mailboxes. Sorted in descending order by GitHub stargazers count.

| Project | Stars | Tech Stack | License | Description |
|:---|:---:|:---|:---|:---|
| **[Chatwoot](https://github.com/chatwoot/chatwoot)** | [![Stars](https://img.shields.io/github/stars/chatwoot/chatwoot?style=social&color=white)](https://github.com/chatwoot/chatwoot/stargazers) | Ruby on Rails, Vue.js, PostgreSQL | AGPL-3.0 | Modern omnichannel customer engagement suite and open-source alternative to Intercom, Zendesk, and Drift. Supports website live chat, WhatsApp, Twitter/X, Facebook, email inboxes, and webhooks. |
| **[UVdesk](https://github.com/uvdesk/community-skeleton)** | [![Stars](https://img.shields.io/github/stars/uvdesk/community-skeleton?style=social&color=white)](https://github.com/uvdesk/community-skeleton/stargazers) | PHP (Symfony), MySQL | OSL-3.0 | Modular open-source ticketing and helpdesk system featuring customer self-service portals, knowledge bases, workflows, and multi-channel ticket dispatching. |
| **[Papercups](https://github.com/papercups-io/papercups)** | [![Stars](https://img.shields.io/github/stars/papercups-io/papercups?style=social&color=white)](https://github.com/papercups-io/papercups/stargazers) | Elixir (Phoenix), React, TypeScript | MIT | Open-source customer messaging platform designed for developers. Embeddable chat widgets, Slack/Mattermost synchronization, and email forwarding capabilities. |
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | Ruby on Rails, Elasticsearch, PostgreSQL | AGPL-3.0 | Full-featured, enterprise-grade open-source Zendesk alternative with built-in migration tools (for Zendesk, Freshdesk, OTRS, Kayako), granular RBAC, audit trails, and BYO-LLM AI capabilities without paywalls. |
| **[FreeScout](https://github.com/freescout-help-desk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-help-desk/freescout?style=social&color=white)](https://github.com/freescout-help-desk/freescout/stargazers) | PHP (Laravel), MySQL | AGPL-3.0 | Super-lightweight open-source Help Scout alternative. Runs easily on minimal hardware (1–2 GB RAM) and cPanel shared hosting with unlimited users, mailboxes, and tickets. Paid optional modules ($12–$15 each) extend functionality. |
| **[osTicket](https://github.com/osTicket/osTicket)** | [![Stars](https://img.shields.io/github/stars/osTicket/osTicket?style=social&color=white)](https://github.com/osTicket/osTicket/stargazers) | PHP, MySQL | GPL-2.0 | Time-tested, reliable email-to-ticket help desk software. Converts inquiries via email, web forms, and phone calls into trackable tickets with configurable SLA metrics and routing rules. |
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | Python (Frappe Framework), Vue.js, MariaDB | AGPL-3.0 | Modern, responsive service desk built on the Frappe framework. Features SLA policies with business hours, automated ticket assignment by skill/load, zero seat limits, and native ERPNext integration. |
| **[Libredesk](https://github.com/abhinavxd/libredesk)** | [![Stars](https://img.shields.io/github/stars/abhinavxd/libredesk?style=social&color=white)](https://github.com/abhinavxd/libredesk/stargazers) | Go (Golang), SQLite / PostgreSQL | MIT | Lightweight single-binary customer support inbox and live chat system designed for ultra-fast and simple self-hosting without heavyweight background worker dependencies. |
| **[Trudesk](https://github.com/polonel/trudesk)** | [![Stars](https://img.shields.io/github/stars/polonel/trudesk?style=social&color=white)](https://github.com/polonel/trudesk/stargazers) | Node.js, MongoDB, Elasticsearch | Apache-2.0 | Clean, open-source real-time ticketing engine with built-in live notifications, SLA management, and customizable support queues. |
| **[Request Tracker (RT)](https://github.com/bestpractical/rt)** | [![Stars](https://img.shields.io/github/stars/bestpractical/rt?style=social&color=white)](https://github.com/bestpractical/rt/stargazers) | Perl, PostgreSQL / MySQL | GPL-2.0 | Heavy-duty, industrial ticket tracking system with unmatched granular access rights per queue, role, and custom field, complete with asset management and deep REST 2 API capabilities. |
| **[OTOBO](https://github.com/rotheross/otobo)** | [![Stars](https://img.shields.io/github/stars/rotheross/otobo?style=social&color=white)](https://github.com/rotheross/otobo/stargazers) | Perl, MariaDB / MySQL | GPL-3.0 | Complete open-source ITIL service desk and IT Service Management (ITSM) platform with comprehensive Configuration Management Database (CMDB) and self-service customer portal. |

---

## Feature Matrix & Selection Guide

- **Best for Enterprise ITIL & Complex ITSM**: [ServiceNow CSM](https://www.servicenow.com/) (commercial) or [OTOBO](https://github.com/rotheross/otobo) (open source).
- **Best Zendesk Alternative (Self-Hosted)**: [Zammad](https://github.com/zammad/zammad) for 1:1 enterprise feature parity with zero seat costs, or [Chatwoot](https://github.com/chatwoot/chatwoot) for omnichannel live messaging and bots.
- **Best for Small Teams & Minimal Overhead**: [Help Scout](https://www.helpscout.com/) (commercial) or [FreeScout](https://github.com/freescout-help-desk/freescout) (open source, runs on $5/mo VPS or shared hosting).
- **Best for E-Commerce Stores (Shopify/Magento)**: [Gorgias](https://www.gorgias.com/).
- **Best Developer & Jira Integration**: [Jira Service Management](https://www.atlassian.com/software/jira/service-management).

---

## How to Contribute

1. Fork this repository.
2. Edit `README.md` to submit your tool or update pricing/stars.
3. Ensure every SaaS entry includes precise starting tier pricing and specific trial or free tier boundaries.
4. Ensure open-source additions include social star badge markdown pointing to the stargazer page (`https://img.shields.io/github/stars/<owner>/<repo>?style=social&color=white`).
5. Open a Pull Request with a clear description of changes.

---

## Disclaimer & Evaluation Notes

- This repository is maintained as a community-curated reference list. Mention does not constitute an endorsement.
- Support desks store sensitive customer Personally Identifiable Information (PII). Ensure appropriate encryption, automated backups, and GDPR/SOC-2 compliance whether self-hosting or purchasing SaaS.
- **TCO & AI Billing Considerations**: 
  - Open-source helpdesk solutions save per-agent licensing fees, but require server maintenance, monitoring, and backup infrastructure (e.g., Zammad recommends 6 GB+ RAM plus Elasticsearch; OTOBO requires 8–16 GB RAM).
  - Modern SaaS pricing models are rapidly evolving: several platforms now charge per resolution outcome (e.g., Intercom Fin at $0.99 per outcome; Jira Service Management Customer Service add-on at $1 per resolution). High ticket volumes can alter total monthly expenditure significantly beyond baseline per-seat costs.
