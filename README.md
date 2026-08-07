<div align="center">

# Isai Guerrero

**AI Enablement · Product Operations**

I build the CRM, eligibility, and automation systems that sales and ops teams run on.<br>
I use AI to build them faster.

</div>

## What I do

**Product Operations.** I turn messy go-to-market and lifecycle processes into working systems: lead and deal pipelines, outreach sequencing, eligibility rules, reporting.

**AI Enablement.** I build agent workflows and LLM pipelines into the tools the team uses every day. I use Claude Code heavily: custom skills, review subagents, multi-agent workflows.

**Building.** Full-stack in TypeScript, from the Postgres schema to the UI.

## Featured work

The repos below are private, so here's what each one does.

**Power Concierge** — revenue platform for a $10M/yr real-estate marketing company, in production<br>
I helped replace HubSpot and an outside development agency with software the company owns. Signals, deals, tasks, billing, inbox, and attribution all read the same records, and support headcount dropped by half. The systems inside it:

- **Signal chain** — a buying signal opens a deal, tasks the right rep, and starts a cadence, hands-free. Every new automation runs in shadow mode for weeks, logging what it would have done, before it's allowed to act.
- **Automated outreach** — watches listing feeds and sends 5,000 personally branded pieces a day, each built on the prospect's own listing and branding, with suppression for anyone already mid-conversation.
- **Durable campaign worker** — multi-day sends run as durable workflows on their own cluster, so a deploy, a crash, or a rate limit pauses the work instead of losing it.
- **AI SMS** — customers text in, AI answers from an approved knowledge base with a confidence gate in front of the send. Low-confidence messages escalate to a human, and updates are graded against a golden dataset before they ship.
- **Rep workspace** — a rep's whole day on one screen: queue ordered by timed commitments then revenue risk, call/text/email in the middle, account context beside it. One screen replaced four tools.
- **Billing as a pipeline** — the payment processor is the source of truth. Its events sync into stages the CRM already understands, reconciled to the penny.
- **Webhook ingestion and replay** — every inbound event is logged before it's processed. Failures land in a dead-letter queue and replay safely once the bug behind them is fixed.
- **Deploy safety gate** — the build refuses to publish when the code expects database migrations the target environment hasn't run. No override flag.

`React · Vite · Supabase · Postgres · Deno Edge Functions · Temporal · Twilio · Stripe`

**StayFrank Partner Portal** — fintech home-equity CRM, in production<br>
Eligibility engine across five lending programs (admin-configured, no hardcoded rules), plus lead/deal pipelines, SMS/email sequences, DocuSign contracts, and Gmail/Calendar sync.<br>
`Next.js · Supabase · Postgres · Edge Functions`

**PowerSignals** — GTM intelligence engine<br>
Scores go-to-market activity into a ranked list of who a rep should call next.<br>
`TypeScript · Supabase`

## Toolbox

**Build:** TypeScript, React, Next.js, Astro, Tailwind<br>
**Data & infra:** Supabase, Postgres, Temporal, Cloudflare, Vercel<br>
**AI:** Anthropic Claude, Claude Code, LLM pipelines

<img alt="Core stack: TypeScript, React, Next.js, Node.js, Supabase, PostgreSQL, Tailwind CSS, Cloudflare, Astro, Vercel" src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,supabase,postgres,tailwind,cloudflare,astro,vercel&theme=dark" />

## Connect

[LinkedIn](https://www.linkedin.com/in/isai-guerrero/) · isaigramirez@gmail.com
