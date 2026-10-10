# Awesome-Sales-Cadence-Inside-Sales

## Top Sales Cadence & Inside Sales Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Multi-Channel Sequences, Outreach Automation & Self-Hosted Cadence Platforms*  

**Last updated: October 2026**



This repository tracks notable **commercial sales cadence and inside sales platforms** and **open-source projects** that automate multi-channel outreach — email sequences, LinkedIn actions, calling, and follow-ups — to help inside sales teams book more meetings and engage prospects at scale.



**Examples** include Salesforce High Velocity Sales, Salesloft, Outreach, Groove, Apollo.io, Yesware, Mixmax, Mailshake, Woodpecker, and Lemlist (the category leaders).



**Open-source emphasis**: Sales cadence and inside sales automation is a rapidly growing open-source domain. **Signal** leads as an open-source AI sales intelligence and outreach automation platform — the open alternative to Clay, Apollo, and Outreach with signals engine, contact enrichment, and multi-step email sequences . **OutreachPro** brings a complete self-hosted Instantly.ai clone with Claude AI personalization, Apify Google Maps scraping, and a built-in CRM pipeline . **outreach-os** delivers production-ready N8N workflows that replace Apollo.io, Instantly, and Lemlist with a free, self-hosted, AI-powered system . **Prospex** offers an open-source AI-powered GTM automation platform combining lead discovery, AI outreach generation, and CRM management . **Zenvio** provides an all-in-one sales engagement platform with email outreach, WhatsApp/Instagram/Messenger team inbox, and visual automation builder . This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Salesloft](https://www.salesloft.com/)**  

  **The enterprise sales cadence and engagement standard** — multi-channel cadences, conversation intelligence, and revenue intelligence. **Pricing typically $125-$165/seat** with custom enterprise quotes and seat minimums . **Best for enterprise inside sales teams** .



- **[Outreach](https://www.outreach.io/)**  

  **Leading sales engagement platform** — sequences, deal intelligence, and revenue operations. **Pricing typically $100-$160/seat** with custom quotes and dialer as separate add-on . **Best for data-driven sales organizations** .



- **[Apollo.io](https://www.apollo.io/)**  

  **All-in-one sales intelligence and engagement** — 275M+ contact database, email sequences, and dialer. **Pricing from ~$49-$99/user/month** with free tier available . **Best for SMBs wanting data + outreach in one** .



- **[Groove](https://www.groove.co/)**  

  **Sales engagement for Salesforce** — native integration with Salesforce for activity capture and sequences. **Best for Salesforce-centric teams** .



- **[Yesware](https://www.yesware.com/)**  

  **Email engagement for Gmail and Outlook** — tracking, templates, and sequences. **Best for individual reps and small teams** .



- **[Mixmax](https://mixmax.com/)**  

  **Email engagement with scheduling** — sequences, polls, and meeting scheduling. **Pricing from ~$9-$49/user/month** with free tier . **Best for Gmail power users** .



- **[Mailshake](https://mailshake.com/)**  

  **Cold email and sales engagement** — sequences, lead catcher, and phone dialer. **Best for cold outreach focused teams** .



- **[Woodpecker](https://woodpecker.co/)**  

  **Cold email automation** — sequences, A/B testing, and deliverability tools. **Best for agencies and SMBs** .



- **[Lemlist](https://lemlist.com/)**  

  **Cold email specialist with personalization** — custom images/video, multichannel sequences (email, LinkedIn, calls), and lemwarm deliverability tool. **Pricing: Email Pro $79/user/month monthly ($63 annual), Multichannel Expert $109/user/month ($87 annual)** . **Best for cold email and multichannel campaigns focused on deliverability** .



- **[Salesforce High Velocity Sales](https://www.salesforce.com/)**  

  **Salesforce's native sales cadence** — work queues, cadences, and Einstein AI integration. **Best for Salesforce customers** .



## Open-Source GitHub Projects



### Full Sales Engagement Platforms



- **[Signal](https://github.com/jay-sahnan/signal)**  

  **Open-source AI sales intelligence and outreach automation**, open-source . **The open alternative to Clay, Apollo, and Outreach — run it on your own keys**  . **Signals engine** — authorable "recipes" that watch companies and surface buying triggers (hiring changes, funding news, product launches, review shifts) . **Contact enrichment** — pulls LinkedIn, GitHub, and company pages into a single profile . **Outreach sequences** — multi-step emails sent from your own Gmail with reply/bounce tracking . **Browser automation** — Browserbase + Stagehand for sites without APIs . **Own your data** — Postgres + RLS on your own Supabase; bring your own LLM keys . **Tech stack**: Next.js 16, Supabase, Anthropic Claude, Tailwind CSS 4 . **Best for AI-powered signal-based outreach** .



- **[OutreachPro](https://www.npmjs.com/package/outreachpro)**  

  **AI-powered B2B sales engagement platform — self-hosted Instantly.ai clone**, MIT licensed  . **Google Maps scraper** — find local businesses via Apify, auto-import leads . **Claude AI personalisation** — unique opening line per lead using business data . **Campaign sequences** — multi-step emails with delays, stop-on-reply, daily limits . **Unibox** — unified reply inbox with AI auto-labelling (Interested / Not now / Meeting) . **CRM pipeline** — Kanban from Prospect → Won, drag-and-drop, pipeline value . **Email warmup** — slow-ramp sending to build sender reputation . **6-language i18n** — EN / DE / FR / ES / IT / NL . **One Docker command to run**  . **Best for self-hosted cold email with AI personalization** .



- **[Zenvio](https://github.com/SarmadSalee/Zenvio)**  

  **All-in-one sales engagement platform for outbound teams**, open-source  . **Email outreach** — multi-step campaigns with delays, follow-ups, open/reply tracking, per-account rate limits, and stop conditions (reply / opt-out / unsubscribe / bounce) . **WhatsApp Cloud API** — team inbox, conversations, message templates, and webhook handling via Meta . **Instagram & Facebook Messenger** — connect Meta Pages in one click, unified team inbox, inbound webhooks, and outbound replies . **CRM** — pipelines, deals, stages, leads, companies, contacts, tags, and custom fields . **Automation** — visual automation builder with nodes and executions . **Deliverability** — domain health checks (SPF/DKIM/DMARC/MX/blacklist), mailbox warm-up, and daily limits . **Billing** — Stripe subscription plans . **Best for teams wanting email + social messaging outreach in one platform** .



### Lead Discovery & Outreach Automation



- **[Prospex](https://github.com/asiifdev/business-leads-ai-automation)**  

  **Open-source AI-powered GTM automation platform**, open-source  . **Think Apollo.io + Instantly.ai — but open-source, self-hosted, and free**  . **Lead Discovery** — scrape Google Maps with AI-powered lead scoring . **AI Content Engine** — personalized Email, WhatsApp, Instagram DM, LinkedIn, Cold Call scripts per lead . **Campaign Manager** — multi-query batch campaigns with real-time progress tracking . **CRM Pipeline** — full lead lifecycle: New → Contacted → Replied → Won/Lost . **Analytics** — conversion funnel, industry breakdown, campaign ROI . **Tech stack**: Next.js 16, NestJS 10, PostgreSQL 16, BullMQ + Redis 7 . **Best for SMEs and agencies wanting full GTM automation** .



- **[outreach-os](https://github.com/hitb1099/outreach-os)**  

  **Open-source AI-powered B2B outreach system using N8N workflows**, open-source  . **Replaces expensive tools like Apollo.io, Instantly, and Lemlist** with a free, self-hosted, AI-powered system you fully own  . **Three production-ready N8N workflows**: Lead Search & Scoring Engine (Google Places, 100-point scoring across 6 dimensions, HOT vs NURTURE output), AI Email Automation (industry detection, Pollinations banner generation, GLM-4 personalized email via Gmail), and Email Reply Tracker & Auto Follow-Up (daily Gmail checks, AI follow-up after 3 days) . **Full status tracking** — Pending → Emailed → Replied / FollowedUp in Google Sheets . **Zero backend required** — runs entirely in N8N  . **Best for teams wanting free, N8N-based outreach automation** .



### Additional Strong Open-Source Options



- **profullstack/lead-generator** — CLI tool and Node.js module for mass lead emails with AI-powered personalization and automated voice cold-calling  .

- **Rohini4228/cold-email-cli** — Cold Email CLI with 627+ commands for 10 platforms, TypeScript-based  .

- **Ansh2709/AI_Agent_for_cold_call** — Hinglish-speaking AI cold call agent using Gemini API for NLG, speech recognition, and TTS  .

- **AI Sales Platform (Tauri + React + Rust + Gemini)** — Open-source AI sales platform with strategist, lead researcher, voice caller, coach, and manager — all on your desktop. AI cold calling, objection handling, post-call debrief, sentiment analysis, Kanban CRM. No SaaS fees  .

- **Open-source cold calling CRM** — SIP softphone, lead management, campaigns, call scripts, analytics, REST API, Docker deployment, self-hosted support. Works with SignalWire, Twilio, Telnyx, and custom SIP providers  .

- **Vantora · Alex** — Cold-Calling AI Voice Agent with outbound voice AI with Twilio Media Streams and OpenAI Realtime: CSV lead lists, consent, DNC and calling-hours guards, answering machine detection and a booking webhook  .

- **Open-source TCPA compliance checklist** — CLI for agencies, call centers and teams running outbound calls or AI dialers. Checks local calling windows by area code, scrubs lists against internal do-not-call files and validates consent logs  .



**Frameworks for building custom sales cadence solutions**: Combine **Signal** for AI-powered buying signal detection and signal-based outreach sequences . Use **OutreachPro** for complete self-hosted cold email with Claude AI personalization and CRM pipeline . Deploy **outreach-os** for free N8N-based lead scoring, AI email generation, and auto follow-up . Integrate **Prospex** for full GTM automation with lead discovery and multi-channel AI content generation . Choose **Zenvio** for email + WhatsApp + Instagram + Messenger outreach in one platform . Note that true enterprise sales cadence with multi-channel sequencing, conversation intelligence, and vendor-supported SLAs (Salesloft, Outreach, Apollo.io) remains primarily commercial territory; open-source stacks provide strong lead discovery, AI personalization, and sequence automation foundations that require integration for complete inside sales operations.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Sales cadence platforms handle sensitive prospect data and may process PII. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA, CAN-SPAM, CASL).

- **Email deliverability requires IP reputation management** — self-hosted platforms must warm up IPs, configure SPF/DKIM/DMARC, and monitor blacklists. Commercial platforms provide managed deliverability .

- **LinkedIn automation carries account risk** — server-side login and human-like pacing reduce but do not eliminate the risk of account restrictions. Use responsibly and within LinkedIn's terms of service.

- **License considerations**: Signal is open-source , OutreachPro uses MIT , outreach-os is open-source , Prospex is open-source , and Zenvio is open-source . Verify licensing against your use case before committing.

- The open-source ecosystem provides strong lead discovery, AI personalization, and sequence automation foundations, but **conversation intelligence, real-time coaching, and vendor-supported SLAs** remain primarily commercial offerings.
