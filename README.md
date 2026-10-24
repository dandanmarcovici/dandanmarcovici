# Daniel Marcovici

Product Manager, mechanical engineer before that. Fourteen years in industrial robotic software: building distribution in Asia, integrating it at customer sites, and eventually deciding the product direction.

I landed in product by staying close to real problems long enough that it became the obvious next step. Eight years at Hypertherm since, as Senior Product Owner for Robotmaster and now as PM for the robotic software portfolio.

For the past year I've been building with AI tools: Claude Code, Lovable, n8n, Supabase. The gap between having an idea and testing it in production has shrunk to days. That changes what's worth betting on.

---

## What's Here

**[strategic-council](https://github.com/dandanmarcovici/strategic-council)**
Claude Code skill for pressure-testing consequential decisions: five independent advisers, anonymous peer review, independent Chairman synthesis. Built to fight AI sycophancy, not produce five agreeable opinions dressed up as a council.

**[pm-second-brain](https://github.com/dandanmarcovici/pm-second-brain)**
A second-brain context system for PMs using Claude Code daily: folder structure, file conventions, and a CLAUDE.md pattern that feed the model the right context at the right moment.

**[claude-skills-for-pms](https://github.com/dandanmarcovici/claude-skills-for-pms)**
Templates, frameworks, and skills that plug into pm-second-brain. None shipped as a first draft: each one is the version left after enough real decisions and meetings exposed a gap.

**[claude-code-workflow-for-pms](https://github.com/dandanmarcovici/claude-code-workflow-for-pms)**
The end-to-end sequence I run in Claude Code to design, build, review, and ship real software as a non-developer PM: explore → plan → execute → review → ship. Extracted from a live production app, not written in the abstract. Dev-specific counterpart to claude-skills-for-pms.

---

## Projects

### Active

**[Medical Practice Website + Claude Plugin](https://www.adrianereumatologia.com.br)** · Live · since Aug 2026
Website for my wife's rheumatology practice in São Paulo, on Next.js 16 and Vercel. The site runs its own MCP server with Google sign-in, so she publishes articles from a conversation with Claude on her phone. Each publish is a commit through the GitHub API that triggers a deploy, which makes git the CMS. A Claude plugin adds three skills: publish an article, turn site content into Instagram carousels in her visual identity, and test the connection. Private repos.

**WhatsApp Scheduling Agent** · Pilot · since Apr 2026
AI agent that answers patients of my wife's medical practice on WhatsApp and books, reschedules or confirms appointments against Google Calendar. Built with n8n, the Meta WhatsApp Cloud API, Supabase and OpenAI, with an escalation classifier that alerts the doctor and eval harnesses that run before every prompt change. A Next.js inbox app lets the team follow conversations, pause the agent and reply by hand. In the final pilot phase with beta testers. Private repos.

**RobotM-BR Website**
B2B lead generation site for the authorized Robotmaster distributor in Brazil. Built for search intent from the ground up: semantic HTML, JSON-LD schema, sitemap, localized copy in Portuguese and Spanish. Stack: Next.js App Router, Tailwind, shadcn/ui, Sanity.io, deployed on Vercel.

### Archived

**OpenClaw - Personal AI Agent** · Apr 2026 to Oct 2026
Built a Telegram-based autonomous agent on a reformatted old PC to understand autonomous agent architecture from the inside. It handled reminders, scheduling, and Google Calendar, with model routing between Haiku and Sonnet by complexity. Found a hidden heartbeat burning $2/day in idle tokens and cut overall token usage by over 60%. Retired in October 2026 when I moved to Grok Bot.

**BikeTracker** · Jan 2026 to Aug 2026
Cyclists track bike maintenance through spreadsheets and guesswork. BikeTracker connects to Strava, calculates km since last service per bike, and sends email alerts when attention is needed. Built end-to-end with Lovable, n8n, Supabase, and Claude Code. Shipped as a PWA with RLS, JWT and Edge Functions. Paused in August 2026.

---

## Stack

![Claude Code](https://img.shields.io/badge/Claude_Code-CC785C?style=flat-square)
![Lovable](https://img.shields.io/badge/Lovable-FF3B82?style=flat-square)
![n8n](https://img.shields.io/badge/n8n-EA4B71?style=flat-square&logo=n8n&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3ECF8E?style=flat-square&logo=supabase&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)

---

[danielmarcovici.com](https://danielmarcovici.com/en) · [LinkedIn](https://www.linkedin.com/in/daniel-marcovici)
