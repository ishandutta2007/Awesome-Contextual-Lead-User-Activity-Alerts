# Awesome Contextual Lead & User Activity Alerts [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of leading SaaS products and open-source GitHub projects for B2B website visitor deanonymization, account-based buying intent detection, and real-time sales alert orchestration.

**Contextual Lead & User Activity Alerts** bridge the gap between anonymous web traffic and active sales outreach. By resolving corporate IP addresses, tracking high-intent behavioral actions (pricing visits, docs exploration, feature clicks), and enriching account records, these systems push actionable buying signals straight to Slack, CRM, and sales pipelines when prospects are in-market.

---

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS & Hosted Platforms](#saas--hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [Key Features & Evaluation Criteria](#key-features--evaluation-criteria)
- [How to Build a Self-Hosted Intent Stack](#how-to-build-a-self-hosted-intent-stack)
- [How to Contribute](#how-to-contribute)
- [Privacy & Compliance](#privacy--compliance)

---

## Sector Overview & Market Dynamics

The global B2B buyer intent data and account-based marketing (ABM) market is currently valued at approximately **$2.5B – $3.5B** and is projected to expand at a **11% – 16% CAGR** toward **$7B+ by the mid-2030s**. The industry exhibits **moderate fragmentation**: top enterprise revenue platforms (HubSpot, 6sense, Demandbase, Zoho) command large shares of total contract value via bundled GTM suites, while a dynamic long-tail of agile point solutions and self-serve visitor identification platforms thrive across mid-market and SMB segments.

---

## SaaS & Hosted Platforms

| Product | Company Size / Scale (Valuation / Revenue) | Description | Starting Pricing Tier | Free Tier / Trial Limits |
| :--- | :--- | :--- | :--- | :--- |
| **[HubSpot (Clearbit / Breeze)](https://www.hubspot.com/products/breeze/intelligence)** | ~$30B+ Market Cap / $2.5B+ ARR | Enterprise CRM & marketing automation platform; integrates Clearbit IP-to-company deanonymization and Breeze Buyer Intent natively. | **$20/user/mo** (Starter Core Seat; $10/1k Breeze credit packs) | **No permanent free tier** for Buyer Intent; 14-day free trial on select Hub plans (500 free credits on paid Starter). |
| **[Zoho Signals / SalesIQ](https://www.zoho.com/salesiq/)** | Privately Held / $1.4B+ ARR (Bootstrapped) | Real-time visitor activity alerts and live customer engagement native to the Zoho CRM ecosystem. | **$7/operator/mo** (SalesIQ billed annually; $23/user/mo for Zoho CRM Professional) | **Free forever plan** (up to 3 operators, 10,000 tracked visitors/mo, 100 chat sessions/mo); 15-day free trial on paid tiers. |
| **[6sense](https://6sense.com/)** | $5.2B Valuation / ~$340M ARR | Predictive ABM platform with AI intent modeling across 1st-party web traffic, 3rd-party research signals, and CRM history. | **~$11,000 – $30,000/year** (Entry-level modules; median deployments ~$55,000/yr) | **No permanent free tier**; interactive demo and guided trial via sales only (annual contract required). |
| **[Demandbase](https://www.demandbase.com/)** | ~$320M Funding / >$200M ARR | Enterprise go-to-market and account-based marketing platform combining real-time reverse-IP tracking with B2B advertising. | **~$45,000 – $60,000/year** (~$3,750/mo billed annually for entry tier) | **No permanent free tier**; custom guided sales evaluation only (annual contract required). |
| **[Lead Forensics](https://www.leadforensics.com/)** | Privately Held / ~$45M – $50M ARR | Real-time IP-to-company tracking platform with proprietary enterprise reverse-IP database and automated contact discovery. | **~$6,000/year** (~$500/mo billed annually for low-traffic sites) | **No permanent free tier**; 7-day to 14-day guided trial available after product demonstration. |
| **[Leadfeeder (Dealfront)](https://www.leadfeeder.com/)** | PE-backed / ~$18M ARR | Website visitor identification platform using Google Analytics and DNS telemetry to unmask visiting accounts. | **€79/mo** (~$79/mo billed annually for Discover plan; €113 month-to-month) | **Free forever plan (Lite)** capped at 100 identified companies/mo and 7-day data retention; 14-day full-access free trial. |
| **[UserGems](https://www.usergems.com/)** | ~$100M – $200M Valuation / ~$10M ARR | Relationship intelligence tracking past champions and buyers when they change jobs, combining contact-level intent with CRM triggers. | **$40,000/year** (Core plan, covers up to 4,000 target accounts and 4M platform credits) | **No permanent free tier**; no public self-serve trial (historical CRM record audit via demo only). |
| **[Factors.ai](https://factors.ai/)** | Privately Held / ~$8M ARR | Account-based analytics, multi-touch attribution, and visitor deanonymization tool for product-led and B2B growth teams. | **$199/mo** (Self-serve entry tier; standard analytics at $599/mo billed annually) | **Free forever tier** available (basic visitor de-anonymization and reporting); 14-day trial on Growth tiers. |
| **[Albacross](https://www.albacross.com/)** | Privately Held / ~$2M ARR | European B2B visitor tracking and account intelligence engine heavily optimized for GDPR compliance. | **€79/mo** (Starter plan billed annually, up to 100 identified companies/mo) | **14-day free trial** with full feature access (no credit card required); no permanent free tier. |
| **[Snitcher](https://www.snitcher.com/)** | Bootstrapped / ~$1.2M ARR | Real-time B2B website visitor identification, lead scoring, and instant Slack alert integration. | **$49/mo** (Base tier up to 50 identified companies/mo; ~$35/mo billed annually) | **14-day free trial** with full features and unlimited user seats (no credit card required); no permanent free tier. |

---

## Open-Source GitHub Projects

Curated open-source projects for self-hosted analytics, reverse-IP mapping, B2B lead generation, and automated intent orchestration—ranked by community GitHub stars:

| Project | Stars | Category / Tech Stack | Description |
| :--- | :--- | :--- | :--- |
| **[Twenty](https://github.com/twentyhq/twenty)** | [![Stars](https://img.shields.io/github/stars/twentyhq/twenty?style=social&color=white)](https://github.com/twentyhq/twenty/stargazers) | Modern CRM / TypeScript | Developer-first, modern open-source CRM alternative to Salesforce with clean REST/GraphQL APIs, company relationship tracking, and webhook triggers for inbound lead events. |
| **[PostHog](https://github.com/PostHog/posthog)** | [![Stars](https://img.shields.io/github/stars/PostHog/posthog?style=social&color=white)](https://github.com/PostHog/posthog/stargazers) | Product Analytics / Python & TS | Open-source product analytics suite with event tracking, session replay, feature flags, and custom webhooks to fire real-time sales alerts on high-intent user activity. |
| **[Mautic](https://github.com/mautic/mautic)** | [![Stars](https://img.shields.io/github/stars/mautic/mautic?style=social&color=white)](https://github.com/mautic/mautic/stargazers) | Marketing Automation / PHP | Complete open-source marketing automation platform featuring IP lookup, behavioral lead scoring, user activity monitoring, and dynamic trigger-based alerts. |
| **[OpenOutreach](https://github.com/eracle/OpenOutreach)** | [![Stars](https://img.shields.io/github/stars/eracle/OpenOutreach?style=social&color=white)](https://github.com/eracle/OpenOutreach/stargazers) | AI Outbound / Python | Autonomous AI agent system for B2B lead generation, firmographic matching, email verification, and automated outreach playbooks. |
| **[EspoCRM](https://github.com/espocrm/espocrm)** | [![Stars](https://img.shields.io/github/stars/espocrm/espocrm?style=social&color=white)](https://github.com/espocrm/espocrm/stargazers) | Self-Hosted CRM / PHP | Production-grade open-source CRM with web-to-lead capture forms, account tracking, and automated workflow triggers for sales notifications. |
| **[FORGE (dataforge)](https://github.com/Nuclear-Marmalade/dataforge)** | [![Stars](https://img.shields.io/github/stars/Nuclear-Marmalade/dataforge?style=social&color=white)](https://github.com/Nuclear-Marmalade/dataforge/stargazers) | Data Enrichment / Python | Open-source business data enrichment engine; alternative to Apollo and Clearbit. Enriches business databases using public government records, tech-stack scrapers, and local Ollama LLMs. |
| **[OpenOutFind](https://github.com/eracle/OpenOutFind)** | [![Stars](https://img.shields.io/github/stars/eracle/OpenOutFind?style=social&color=white)](https://github.com/eracle/OpenOutFind/stargazers) | Lead Discovery / Python | Lightweight B2B lead finder and contact extraction script designed for pipeline enrichment and targeted account prospecting. |
| **[p2pblocklists (IP Mapping)](https://github.com/f1lby/p2pblocklists)** | [![Stars](https://img.shields.io/github/stars/f1lby/p2pblocklists?style=social&color=white)](https://github.com/f1lby/p2pblocklists/stargazers) | IP Infrastructure / Shell | Massive IPv4 address database (3B+ addresses) enabling ASN and reverse-IP organization lookup, serving as raw data for self-hosted visitor deanonymization. |
| **[looot-crm](https://github.com/loootai/looot-crm)** | [![Stars](https://img.shields.io/github/stars/loootai/looot-crm?style=social&color=white)](https://github.com/loootai/looot-crm/stargazers) | Modern CRM / Next.js & Supabase | Open-source CRM built on Next.js and Supabase featuring dedicated account-level buying-intent signal tabs and pipeline tracking. |
| **[intent-engine](https://github.com/aria-agentworks/intent-engine)** | [![Stars](https://img.shields.io/github/stars/aria-agentworks/intent-engine?style=social&color=white)](https://github.com/aria-agentworks/intent-engine/stargazers) | Intent Workflows / Python | Open-source lead generation and intent-scoring agentic workspace for researching buyer signals and dispatching outbound actions. |

---

## Key Features & Evaluation Criteria

When selecting a contextual alert platform or engineering your own stack, evaluate against these four core dimensions:

1. **Deanonymization Accuracy & Match Rate**: IP-to-company resolution rate on your target geography (US vs. EU/APAC) and the ability to filter out consumer ISPs (Comcast, Verizon) from commercial domains.
2. **Intent Signal Depth**: Granularity of tracked actions—differentiating generic homepage visits from high-intent actions (pricing page, API documentation, churn/comparison articles).
3. **Real-Time Alert Channels**: Speed and quality of delivery to Slack, Microsoft Teams, Webhooks, or direct CRM task assignments for SDRs.
4. **Data Privacy & Compliance**: Built-in adherence to GDPR, CCPA, and PECL rules regarding IP logging, cookie banners, and individual-level enrichment.

---

## How to Build a Self-Hosted Intent Stack

For engineering teams seeking data sovereignty and predictable infrastructure costs:

```
[ Visitor Hits Website ]
           │
           ▼
[ Open Analytics / Edge Worker (PostHog / Umami) ]
           │
           ├─ Log IP, Page View, Referrer & UTMs
           ▼
[ Reverse-IP & Enrichment Engine (p2pblocklists + FORGE) ]
           │
           ├─ Filter out ISP ranges
           ├─ Resolve Company Domain & Firmographics
           ▼
[ Intent Scoring & Routing (Twenty CRM / Webhook) ]
           │
           ▼
[ Real-Time Alert to Sales (Slack / Email / CRM Pipeline) ]
```

---

## How to Contribute

We welcome additions, corrections, and updates!
1. Fork this repository.
2. Add your SaaS tool or open-source repository into the appropriate table, following existing column formats.
3. Ensure pricing, trial parameters, and star badges are accurate and verified.
4. Open a Pull Request with a concise summary.

---

## Privacy & Compliance

- **Community Curated**: This repository is an informational resource and does not constitute commercial endorsement.
- **Data Protection Regulations**: Tracking visitor activity, processing corporate IP addresses, and enriching contact data must comply with applicable data protection laws, including GDPR (EU/UK), CCPA/CPRA (California), and local privacy mandates. Person-level tracking without explicit consent is restricted across many jurisdictions.
