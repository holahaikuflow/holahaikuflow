# Hi, I'm Víctor Urrutia

**Technical founder and AI Product Engineer building production software end-to-end.**

Founder & CEO of **BookFindería Escuela**, an EdTech platform helping schools connect students with books they are more likely to want to read and can actually access.

I work across product strategy, UX, frontend, backend, databases, AI workflows, infrastructure, testing, and deployment.

BookFindería Escuela is currently running pilots with **two schools in Chile**.

## Selected Work

### BookFindería Escuela

A B2B EdTech platform for Chilean schools focused on reading engagement and personalized book discovery.

As founder and sole product engineer, I designed and built:

- Anonymous student onboarding through QR codes
- Interest-based personalized book recommendations
- Separate student, teacher, and administration workflows
- Teacher dashboards and reading-progress tracking
- Educational book guides and assessment tools
- PostgreSQL data modeling and Row Level Security
- Privacy-by-design architecture for student data
- Production deployment and verification workflows

**Stack:** React, TypeScript, Vite, Tailwind CSS, Supabase, PostgreSQL, Row Level Security, Cloudflare Pages

**Status:** Deployed and currently running pilots with two schools in Chile.

[View the live product](https://bookfinderia.cl/escuela) · [Read the technical case study](https://github.com/holahaikuflow/bookfinderia-escuela-case-study)

> The production repository is private because it contains commercial code, internal documentation, and shared infrastructure.

---

### Desglose AI

An AI-assisted platform for public procurement planning in Chile.

Desglose transforms institutional purchasing needs into structured requirements — items, quantities, specifications, and supporting procurement references — while keeping a human reviewer in control of the final output.

The product is being developed around:

- AI-assisted requirement generation
- Structured purchasing specifications
- Comparable public purchases
- Procurement-data retrieval and ranking
- Traceable budgeting evidence
- Human review before final output

A central engineering challenge is connecting generated requirements with relevant real-world procurement records while keeping source evidence distinct from AI-generated interpretation.

**Status:** Under active development, with current work focused on the **Compras similares** layer and real public procurement evidence.

[Read the technical case study](https://github.com/holahaikuflow/desglose-ai-case-study)

> The public repository documents product and engineering decisions. Proprietary source code, credentials, private infrastructure, and internal operational configuration are intentionally excluded.

---

### Sofía AI Assistant

A production conversational AI and automation system for real-estate lead qualification over WhatsApp.

I designed and evolved a system that:

- Handles real customer conversations through WhatsApp Cloud API
- Queries live property inventory
- Transcribes voice messages with OpenAI Whisper
- Uses structured LLM tool contracts and runtime validation
- Serializes message processing per lead to prevent race conditions
- Applies idempotency protections for repeated webhook deliveries
- Moves critical qualification decisions toward deterministic business rules
- Tracks production errors, latency, token usage, cache behavior, and degraded results
- Supports human takeover through an administrative interface

**Stack:** Cloudflare Workers, JavaScript, Anthropic Claude API, OpenAI Whisper, Supabase, PostgreSQL, React, TypeScript, Resend, WhatsApp Cloud API

[Read the technical case study](https://github.com/holahaikuflow/sofia-ai-assistant-case-study)

> The production repository remains private because it contains commercial code, customer data, credentials, private prompts, and internal operational configuration.

---

### Immo Paraguay Infrastructure Case Study

A multilingual real-estate platform and infrastructure migration combining product engineering, cloud architecture, media optimization, and cost reduction.

The project included:

- A production property platform in five languages
- A custom administration panel
- Supabase and PostgreSQL data workflows
- Google OAuth and Row Level Security
- Migration of more than 190 images from Supabase Storage to Cloudflare R2
- Python automation for asset migration and compression
- Hosting migration from Netlify to Cloudflare Pages
- Infrastructure cost reduction from approximately USD 34/month to USD 0 at the recorded usage level

**Stack:** React, TypeScript, Vite, Supabase, PostgreSQL, Cloudflare Pages, Cloudflare R2, Python, boto3, requests, Pillow

[Read the technical case study](https://github.com/holahaikuflow/immo-paraguay-infrastructure-case-study)

> The production repository remains private because it contains commercial code, infrastructure configuration, and internal operational details.

---

### AI Lead Qualification API

A production-style FastAPI service that converts validated real-estate purchase signals into deterministic and auditable lead classifications.

The API includes:

- Strict request validation with Pydantic
- Decimal-based budget and property-price comparison
- Cold, warm, and hot lead classifications
- Structured reason codes, messages, and awarded points
- 62 automated tests
- Continuous integration across Python 3.11, 3.12, and 3.13
- Public deployment on Render
- Interactive OpenAPI documentation

**Stack:** Python, FastAPI, Pydantic, pytest, GitHub Actions, Render

[View the repository](https://github.com/holahaikuflow/ai-lead-qualification-api) · [Try the live API](https://ai-lead-qualification-api.onrender.com/docs) · [View release v0.2.0](https://github.com/holahaikuflow/ai-lead-qualification-api/releases/tag/v0.2.0)

## Engineering Approach

I build products from problem definition through production operation.

My work typically spans:

- Product discovery and scope
- UX and interface design
- Frontend and backend implementation
- API and third-party integrations
- PostgreSQL data modeling
- Authentication and authorization
- LLM workflows and structured AI outputs
- Testing and production verification
- Cloud infrastructure and deployment
- Reliability, observability, and debugging

I use AI coding tools such as Claude Code, Cursor, and ChatGPT as part of my engineering workflow for investigation, implementation, testing, and documentation.

Architecture, product scope, security decisions, validation, and production deployment remain human-controlled.

## Core Technologies

- TypeScript / JavaScript
- React
- Python
- FastAPI
- PostgreSQL
- Supabase
- REST APIs and webhooks
- Cloudflare Pages and Workers
- Git and GitHub
- LLM APIs
- Structured LLM outputs and tool use
- AI automation workflows

## Languages

- Spanish — Native
- French — C2 / Full professional proficiency
- English — B2 professional working proficiency
- Portuguese — Conversational

## Beyond Software

Alongside building software products, I have published four books in Chile.

Writing has given me another form of long-term project execution: developing complex ideas, working through editorial processes, communicating clearly, and finishing multi-year creative projects.

### Selected Publications

- [*El último viernes*](https://www.libreriadelgam.cl/libro/ultimo-viernes-el_82469) — Novel, Editorial Viuda Negra
- [*Frutos del desierto*](https://www.astroeditora.cl/producto/frutos-del-desierto/) — Astro Editora
- [*Milagro en la selva*](https://www.astroeditora.cl/producto/milagro-en-la-selva/) — Astro Editora
- [*Poemas de Atrapama*](https://www.astroeditora.cl/producto/poemas-de-atrapama/) — Poetry, Astro Editora

## Connect

[LinkedIn](https://www.linkedin.com/in/victorurrutiacisterna/) · [HaikuFlow](https://haikuflow.com) · [BookFindería](https://bookfinderia.cl) · [Email](mailto:hola@haikuflow.com)
