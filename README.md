# Hi, I'm Evan

I'm a software engineer with 5+ years of experience shipping full-stack and AI applications, now focused on product security and secure-by-design AI applications. I work across the stack in React/TypeScript and Python, and I build deterministic guardrails for the places where AI agents meet real systems: access control, untrusted input, and secrets. I came to software from an electrical engineering background.

## Experience

As a Software Engineer at Deloitte (2023 to 2026), I worked on AI applications and clinical systems that handled sensitive client data:

- Led the frontend of a cross-platform Electron app (React/TypeScript, Python/Flask) in Deloitte's Cyber AI practice that runs LLMs on-device to score vendor risk. It was piloted with a Fortune 500 media client and cut a 10-hour review to 10 minutes.
- Owned the API layer as sole full-stack engineer on an agentic AI permitting app: FastAPI backend, React/TypeScript frontend, deployed to AWS (S3, DynamoDB, App Runner) with Terraform.
- Shipped the React notifications feature for Navy clinical systems serving 30,000+ users, integrated with a Java backend and PostgreSQL.

Earlier, I shipped high-traffic e-commerce storefronts (Next.js/Vue) and React dashboards and client portals. B.S. in Electrical Engineering, George Mason University.

## What I work with

- **Languages:** TypeScript, JavaScript, Python
- **Frontend:** React, Next.js, Vue, Electron, Tailwind
- **Backend:** FastAPI, Flask, Node.js, REST APIs, Kafka, gRPC
- **Databases:** PostgreSQL (Neon, Supabase), MySQL, DynamoDB
- **Cloud & DevOps:** AWS (Lambda, API Gateway, S3, App Runner, CDK), Cloudflare Workers, Terraform, Docker, GitHub Actions, Azure DevOps
- **AI:** LLM APIs, structured output, RAG, on-device LLMs, MCP, agentic workflows, Claude Code
- **Security:** JWT/OAuth, access control, Postgres Row-Level Security, SSRF defense, secret/PII redaction, threat modeling (STRIDE), OWASP Top 10 for LLMs, SAST/SCA/secret-scanning CI
- **Integrations:** Stripe, Microsoft Graph

## Selected projects

Recent work:

- [MCP Guardrail Gateway](https://github.com/evwalt/mcp-guardrail-gateway) (open source, November 2026): A deterministic security layer that wraps an LLM agent's tool calls with JWT session binding against cross-tenant access, SSRF defense, and secret/PII redaction, plus a red-team suite mapped to the OWASP Top 10 for LLMs and SAST/SCA/secret-scanning CI. `Python` · `MCP` · `Security`
- [Genawatt Saver](https://genawatt.com) (client project, October 2026): A web app that lets California electricity customers upload an SDG&E bill, see if they're overpaying, and pay for a switch to a better rate plan. Includes SharePoint (Microsoft Graph API) and Stripe integrations. Sole engineer; launched two weeks after contract. `Next.js` · `TypeScript` · `Microsoft Graph` · `Stripe`
- [Ambler](https://ambler.website) (independent venture, October 2026, unlaunched): A daily walking-route app. Prelaunch: email signup, Postgres, analytics, and a Stripe pre-sale, running on Cloudflare Workers. `Next.js` · `Neon Postgres` · `PostHog` · `Stripe` · `Cloudflare Workers`

A few more things I've built outside work:

- [RLS Guard](https://rls-guard.evanwalter.dev/) (July 2026): A developer security tool that audits Supabase/Postgres projects for broken access control (missing or misconfigured Row-Level Security) and generates ready-to-run remediation SQL, with analysis running entirely in the browser. `Next.js` · `TypeScript` · `PostgreSQL` · `Supabase`
- [opsflow-ai](https://github.com/evwalt/opsflow-ai) (August 2026): A full-stack app that turns unstructured operational requests into typed, schema-validated workflow and action-item objects using an LLM with structured output. `Next.js` · `TypeScript` · `LLM APIs` · `Zod`
- [amazon-connect-contact-center](https://github.com/evwalt/amazon-connect-contact-center) (June 2026): A serverless Amazon Connect contact center that converts caller numbers to vanity numbers, ranks and stores them in DynamoDB, and shows recent call activity in a React dashboard. `Node.js` · `AWS Lambda` · `DynamoDB` · `API Gateway` · `AWS CDK` · `React`
- [identity-sync-pipeline](https://github.com/evwalt/identity-sync-pipeline) (November 2026): An event-driven pipeline that syncs non-human identity changes (service accounts, API keys, AI agents) through Kafka into Postgres and serves access lookups over gRPC, with idempotent consumers, stale-event protection, and dead-letter handling. `Python` · `Kafka` · `PostgreSQL` · `gRPC`
- [tactical-telemetry](https://github.com/evwalt/tactical-telemetry) (August 2026): A distributed system that simulates an unmanned vehicle streaming telemetry as Cursor-on-Target messages over UDP, with a ground station that tracks state and flags dropped, stale, and out-of-order packets. `C#` · `.NET` · `UDP` · `Serilog`

## Certifications & awards

- [Fundamentals of Accelerated Computing with CUDA Python](https://learn.nvidia.com/certificates?id=U16qeCFNQd6n5q1BHhc-4Q), NVIDIA (2024)
- Deloitte Outstanding Performance Awards (2024, 2025), including one for the Cyber AI risk-scoring app
- DoD Secret clearance (inactive, eligible for reactivation)

## Setup & interests

I work keyboard-first rather than mouse-first, and add voice where it's faster: I dictate with [Handy](https://github.com/cjpais/Handy) for talking through tasks with AI tools. For the keyboard side I use [Neovim](https://github.com/evwalt/dotfiles/tree/main/.config/nvim) and [Hammerspoon](https://github.com/evwalt/dotfiles/blob/main/.hammerspoon/init.lua) for window management, all in my [dotfiles](https://github.com/evwalt/dotfiles). I type in Dvorak on a tented [Lily58](https://github.com/kata0510/Lily58) with custom [QMK](https://qmk.fm) firmware, and use [Typst](https://typst.app) for structured PDFs.

I've been a guest on [The React Show](https://www.thereactshow.com/podcast/from-a-career-in-logic-gates-to-react-with-evan-walter) to talk about my path from electrical engineering to software.

## Outside software

Hiking ⛰️, fitness 💪, travel ✈️, and time with family and friends 👨‍👩‍👧‍👦.
