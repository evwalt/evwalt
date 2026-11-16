# Hi, I'm Evan

I'm a software engineer with 5+ years of experience building full-stack and AI-enabled systems, now focused on product security and secure-by-design AI applications. I work across the stack in React/TypeScript and Python, and I build deterministic guardrails for the places where AI agents meet real systems: access control, untrusted input, and secrets. I came to software from an electrical engineering background.

## Experience

As a Software Engineer at Deloitte, I built internal, AI-integrated web applications for federal and healthcare-adjacent clients:

- Built Python-backed internal services for clinical systems supporting 30,000+ users.
- Built a full-stack agentic AI permitting application: FastAPI backend, React/TypeScript frontend, deployed on AWS (S3, DynamoDB, App Runner) with Terraform.
- Built a cross-platform desktop app (React/TypeScript, Electron, Flask) that integrated LLM APIs into internal automation workflows.

Before that I built high-traffic e-commerce front ends (Next.js/Vue) and client dashboards and portals. B.S. in Electrical Engineering, George Mason University.

## What I work with

- **Languages:** TypeScript, JavaScript, Python, and more
- **Frontend:** React, Next.js
- **Backend:** FastAPI, Flask, Node.js, REST APIs
- **Cloud & data:** AWS (Lambda, S3, DynamoDB, App Runner), Terraform, Docker
- **AI:** LLM APIs, structured output, AI-enabled automation
- **Security:** JWT/OAuth, access control, SSRF defense, secret/PII redaction, threat modeling (STRIDE), SAST/SCA/secret-scanning CI

## Selected projects

Recent work:

- [MCP Guardrail Gateway](https://github.com/evwalt/mcp-guardrail-gateway) (open source, November 2026): A deterministic security layer that wraps an LLM agent's tool calls with JWT session binding against cross-tenant access, SSRF defense, and secret/PII redaction, plus a red-team suite mapped to the OWASP Top 10 for LLMs and SAST/SCA/secret-scanning CI. `Python` · `MCP` · `Security`
- [GenaWatt](https://genawatt.com) (client project, October 2026): A web app that lets California electricity customers upload an SDG&E bill, see if they're overpaying, and pay to be moved to a better rate plan. Includes SharePoint (Microsoft Graph API) and Stripe integrations, with tests. `Next.js` · `TypeScript` · `Microsoft Graph` · `Stripe`
- [Ambler](https://ambler.website) (independent venture, October 2026, unlaunched): A daily walking-route app. The prelaunch build has email signup, Postgres, analytics, and a Stripe pre-sale, running on Cloudflare Workers. `Next.js` · `Neon Postgres` · `PostHog` · `Stripe` · `Cloudflare Workers`

A few more things I've built outside work:

- [RLS Guard](https://rls-guard.evanwalter.dev/): A developer security tool that audits Supabase/Postgres projects for broken access control (missing or misconfigured Row-Level Security) and generates ready-to-run remediation SQL, with analysis running entirely in the browser.
- [opsflow-ai](https://github.com/evwalt/opsflow-ai): A full-stack app that turns unstructured operational requests into typed, schema-validated workflow and action-item objects using an LLM with structured output. `Next.js` · `TypeScript` · `LLM APIs` · `Zod`
- [amazon-connect-contact-center](https://github.com/evwalt/amazon-connect-contact-center): A serverless Amazon Connect contact center that converts caller numbers to vanity numbers, ranks and stores them in DynamoDB, and shows recent call activity in a React dashboard. `Node.js` · `AWS Lambda` · `DynamoDB` · `API Gateway` · `AWS CDK` · `React`
- [tactical-telemetry](https://github.com/evwalt/tactical-telemetry): A distributed system that simulates an unmanned vehicle streaming telemetry as Cursor-on-Target messages over UDP, with a ground station that tracks state and flags dropped, stale, and out-of-order packets. `C#` · `.NET` · `UDP` · `Serilog`

## Setup & interests

I work keyboard-first rather than mouse-first, and add voice where it's faster: I dictate with [Handy](https://github.com/cjpais/Handy) and [Whisper](https://github.com/openai/whisper), which works well for talking through tasks with AI tools. For the keyboard side I use [Neovim](https://github.com/evwalt/dotfiles/tree/main/.config/nvim) and [Hammerspoon](https://github.com/evwalt/dotfiles/blob/main/.hammerspoon/init.lua) for window management. I type in Dvorak on a tented [Lily58](https://github.com/kata0510/Lily58) with custom [QMK](https://qmk.fm) firmware, and use [Typst](https://typst.app) for structured PDFs. It's all in my [dotfiles](https://github.com/evwalt/dotfiles).

I've been a guest on [The React Show](https://www.thereactshow.com/podcast/from-a-career-in-logic-gates-to-react-with-evan-walter) (my path from electrical engineering to React) and again to talk [keyboard layouts and editors](https://www.thereactshow.com/podcast/dvorak-vs-qwerty-vim-vs-vscode-Rust-and-design-by-contract).

## Outside software

Hiking ⛰️, fitness 💪, travel ✈️, and time with family and friends 👨‍👩‍👧‍👦.
