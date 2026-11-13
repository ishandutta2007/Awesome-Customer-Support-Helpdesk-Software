# Awesome-Customer-Support-Helpdesk-Software

# Top Customer Support & Helpdesk Software Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Ticket Management, Shared Inboxes & Omnichannel Customer Support*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Support & Helpdesk Software**. These tools help support teams manage incoming requests across email, chat, phone, and social channels—consolidating conversations, automating routing, and tracking resolution metrics so nothing falls through the cracks.

**Examples** include Zendesk Support, Freshdesk, ServiceNow CSM, Help Scout, Intercom, Gorgias, Jira Service Management, Front, LiveAgent, Deskpro, and open-source alternatives like Zammad, FreeScout, and osTicket (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted helpdesk platforms, open-source ticketing systems, and community-driven shared inboxes—ideal for organizations seeking data sovereignty and eliminating per-agent licensing costs. The open-source helpdesk landscape is mature and production-ready: Zammad offers the closest Zendesk-like experience with no feature paywalls, FreeScout nails the Help Scout shared-inbox model on minimal hardware, and osTicket handles simple email-to-ticket workflows [citation:3][citation:4].

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Zendesk Support](https://www.zendesk.com/)** | Industry-standard ticketing platform with mature omnichannel queues, strong reporting, and a broad integration ecosystem. Enterprise reviewers consistently rate it highly for reliability and coverage across large review bases [citation:1]. **Standalone Support Team is $19/agent/month** (annual), distinct from Zendesk Suite pricing. Zendesk is transitioning to **Outcome AI Platform** with outcome-based pricing (unlimited seats, pay for eligible outcomes) in Early Access [citation:14]. | Support Team: **$19/agent/month** (annual); Suite Team: $55; Suite Professional: $115 [citation:14] | No free tier; trial via sales. AI resolution allowances vary by account [citation:14] |
| **[Freshdesk](https://www.freshworks.com/freshdesk/)** | Cloud helpdesk with AI-powered service (Freddy). Growth tier covers email support; Pro adds custom dashboards and round-robin assignment; Enterprise adds skill-based routing and audit logs. **Standalone helpdesk pricing is distinct from Freshdesk Omni** (omnichannel family) [citation:14]. | Growth: **$19/agent/month** (annual); Pro: $55; Enterprise: $89 [citation:14] | No permanent free tier; trial available. Freddy AI Agent: 500 free sessions, then $49/100 [citation:14] |
| **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)** | Atlassian's service management platform. **Free tier: 3 agents, unlimited customers**. Premium adds 24/7 support and advanced automation. Rovo AI credits included on paid plans. Customer Service Management adds **$1 per resolution** on top of agent seats. | Premium: **$55.28/agent/month** | **Free**: 3 agents, unlimited customers, 2 GB storage, 100 emails/day |
| **[Help Scout](https://www.helpscout.com/)** | Shared inbox focused on conversation quality. Standard adds AI Inbox assistant; Plus adds unlimited AI Drafts. **Docs (knowledge base) costs $10/user/month extra on Standard**—making Standard+Docs ($35) nearly comparable to Plus ($50). | Standard: **$25/user/month** (annual); Plus: $50; Pro: $65 | **Free**: 5 users, 1 Inbox, 1 Docs site |
| **[Intercom](https://www.intercom.com/)** | AI-first customer service platform. **Fin AI agent** resolves conversations autonomously at **$0.99 per outcome**; Copilot assists human agents (10 conversations/month included, unlimited at $35/user/month). Fin outcomes often dominate the bill at scale. | Essential: **$29/seat/month** (annual); Advanced: $85 | No permanent free tier; trial available. Fin outcome pricing: $0.99 each |
| **[Front](https://front.com/)** | Collaborative inbox for shared email, chat, and messaging. Starter supports single channel type; Professional adds omnichannel and macros. 14-day trial of Professional (no credit card). | Starter: **$25/seat/month**; Professional: $65; Enterprise: $105 | **14-day free trial** of Professional |
| **[LiveAgent](https://www.liveagent.com/)** | Helpdesk with universal inbox for tickets, chats, calls, and social. **AI assistants run on your own AI provider account**—LiveAgent does not charge for AI usage. Starter up to 5 agents; Enterprise flat fee with 80 agents included. | Starter/Team/Business: per-agent; Enterprise: flat fee + 80 agents | Free trial available; no permanent free tier |
| **[Gorgias](https://www.gorgias.com/)** | E-commerce-focused helpdesk (Shopify, BigCommerce, Magento). Automates order-related tickets with macros and intent-based routing. Plans scale by ticket volume rather than seats. | Quote-only (ticket-volume based) | Free trial available; no permanent free tier |
| **[Deskpro](https://www.deskpro.com/)** | Helpdesk with multi-channel support and customizable ticket workflows. Positioned for teams needing flexibility without enterprise complexity. | Quote-only | Free trial available |
| **[ServiceNow CSM](https://www.servicenow.com/)** | Enterprise customer service management. **Fulfiller seats roughly $100–$200/user/month** at smallest band, falling above 2,500 seats. Now Assist AI adds $25–$75/fulfiller/month on pre-2026 contracts; April 2026 tiers include AI with assist allocation. | Quote-only; ~$100–$200/fulfiller/month (smallest band) | No free tier; demo via sales |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Zammad](https://github.com/zammad/zammad)** | [![Stars](https://img.shields.io/github/stars/zammad/zammad?style=social&color=white)](https://github.com/zammad/zammad/stargazers) | **The closest open-source Zendesk alternative and the only tool with built-in importers for Zendesk, Freshdesk, Kayako, and OTRS** [citation:11]. AGPL-3.0, Ruby on Rails. **No feature paywalls**—SAML, OIDC, roles, audit logs, and AI features (bring-your-own model via OpenAI, Anthropic, Mistral, or local Ollama) are all in the free self-hosted edition [citation:4][citation:11]. **Needs 6 GB RAM minimum, plus 4 GB for Elasticsearch** [citation:11]. 65,000+ organizations worldwide; 10-year track record [citation:4]. |
| **[FreeScout](https://github.com/freescout-help-desk/freescout)** | [![Stars](https://img.shields.io/github/stars/freescout-help-desk/freescout?style=social&color=white)](https://github.com/freescout-help-desk/freescout/stargazers) | **The best open-source Help Scout-style shared inbox.** ~10MB PHP/Laravel distribution. **No limitations on users, tickets, or mailboxes** . Runs comfortably on **1–2 GB RAM** and is the only tool designed for shared hosting [citation:3]. Core software is free; **SLA management, knowledge base, and customer portal are paid modules ($12–$15 each)**—factor these into TCO [citation:12]. Best for small teams, nonprofits, and installs where speed matters more than feature depth. |
| **[osTicket](https://github.com/osTicket/osTicket)** | [![Stars](https://img.shields.io/github/stars/osTicket/osTicket?style=social&color=white)](https://github.com/osTicket/osTicket/stargazers) | **Straightforward email-to-ticket system** for teams with limited process complexity [citation:3]. PHP/MySQL (PHP 8.2–8.4, MySQL 5.5+). Lightweight (1–2 GB RAM). Converts email, phone, and web forms into tickets with SLA policies, agent assignment, and threaded histories [citation:6][citation:13]. API is functional but limited in scope. Best when you just need email turned into tickets without a modern, deeply integrated platform. |
| **[OTRS/OTOBO](https://github.com/rotheross/otobo)** | [![Stars](https://img.shields.io/github/stars/rotheross/otobo?style=social&color=white)](https://github.com/rotheross/otobo/stargazers) | **Full ITIL service desk with customer self-service portal.** OTOBO is a fork of OTRS Community Edition, started in 2019 to keep the tool 100% free [citation:10]. Includes ITSM packages with CMDB at no cost. **Production servers need at least 8 GB RAM, 16 GB recommended** [citation:3]. Vendor support from €3,900/year. Best for IT teams wanting OTRS-style service desk without licence fees [citation:3]. |
| **[UVdesk](https://github.com/uvdesk/uvdesk)** | [![Stars](https://img.shields.io/github/stars/uvdesk/uvdesk?style=social&color=white)](https://github.com/uvdesk/uvdesk/stargazers) | Open-source helpdesk with **customer-facing portal emphasis**. Symfony/PHP, OSL-3.0. Unlimited agents, teams, and mailboxes in the free edition. Includes email ticketing, knowledge base, canned responses, and support center portal [citation:3][citation:7]. **No SSO for agents and no audit log**; no new release since v1.1.8 in September 2025—check recent activity before committing [citation:3]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Request Tracker (RT)](https://github.com/bestpractical/rt)** | [![Stars](https://img.shields.io/github/stars/bestpractical/rt?style=social&color=white)](https://github.com/bestpractical/rt/stargazers) | **Best for complex queues and granular permissions.** Rights can be set per queue, group, and role; asset tracking built in; REST 2 API included. GPL-2.0, Perl source install. **No official Docker image for production**; SSO needs a web server module [citation:3]. |
| **[Frappe Helpdesk](https://github.com/frappe/helpdesk)** | [![Stars](https://img.shields.io/github/stars/frappe/helpdesk?style=social&color=white)](https://github.com/frappe/helpdesk/stargazers) | Open-source ticketing built on Frappe framework (Python/Vue). SLAs with business hours, auto-assignment by priority/type/team/workload, unlimited agents with no seat fees, Google/Microsoft/OIDC sign-in, customer sync with ERPNext. **No live chat or WhatsApp channel**; self-hosting means running the full Frappe stack (MariaDB, Redis, bench) [citation:3]. |
| **[Libredesk](https://github.com/abhinavxd/libredesk)** | [![Stars](https://img.shields.io/github/stars/abhinavxd/libredesk?style=social&color=white)](https://github.com/abhinavxd/libredesk/stargazers) | Open-source customer support inbox for email and live chat, written in Go. **Single Go binary**—significantly simpler deployment than PHP or Ruby stacks [citation:3]. Newer project worth watching for teams wanting minimal infrastructure footprint. |

**Frameworks for building custom systems**: Choose **Zammad** for Zendesk-like breadth with no feature paywalls and SSO included, **FreeScout** for a lightweight shared-inbox model on minimal hardware, **osTicket** for simple email-to-ticket, and **OTOBO** when ITIL service management and CMDB are required—all deployable on a $10–$20/month VPS [citation:3]. For granular permission control, **Request Tracker** remains unmatched [citation:3].

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Helpdesk platforms handle customer PII and support conversations; enforce role-based access, audit logging, and compliance with applicable data protection regulations.
- **Open-source helpdesk TCO is not zero.** FreeScout gates SLA management, knowledge base, and customer portal behind paid modules ($12–$15 each) [citation:12]. Zammad needs 6 GB RAM minimum plus Elasticsearch overhead [citation:11]. OTOBO needs 8–16 GB RAM for production [citation:3]. Budget infrastructure ($10–$20/month VPS), admin time, backups, and security hardening. **SaaS pricing is shifting toward AI outcomes.** Intercom's Fin at $0.99 per outcome can dwarf seat costs at scale—a 10-agent team with 2,000 resolutions/month pays **$1,980 in Fin outcomes alone** vs. $850 in seats. Zendesk is moving to outcome-based billing with unlimited seats [citation:14]. Verify current pricing against vendor pages before committing.

---

**Made for support operations managers, helpdesk administrators, IT service teams, and developers building customer service infrastructure.**  
Let's make customer support helpdesk software more open, affordable, and agent-friendly.
