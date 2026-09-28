# Developer Profile

## Full-Stack Product Developer

Full-stack product developer and software builder with a strong frontend background, particularly in React and TypeScript.

**Frontend and React are my strongest areas**, where I focus on building complex, interactive, user-oriented interfaces. I also work across backend, data, AI, testing, integrations, and deployment to take products end-to-end.

---

## Builder Mindset

**Product-oriented, end-to-end software builder.**

I turn concrete user needs and ambiguous requirements into working, deployable products.

**Product → UX → Architecture → Implementation → Testing → Deployment**

### What distinguishes my approach

- **UX-first product thinking** — I start from the user experience and derive the technical architecture from it.
- **End-to-end ownership** — Frontend, backend, data, AI, integrations, testing, and deployment.
- **Cross-domain** — Web apps, data platforms, AI applications, desktop software, developer tools, and Figma plugins.
- **Technology-independent** — Comfortable learning unfamiliar technologies when the product requires them.
- **Systems thinking** — I consider APIs, persistence, async processing, reliability, testing, and operational concerns as part of the product.
- **Build-first mindset** — I prefer turning ideas into working software and learning through implementation.

---

## Development Workflow

```text
Issue
  ↓
Architecture
  ↓
Implementation
  ↓
Tests
  ↓
Integration
  ↓
Pull Request
  ↓
Review / CI
  ↓
Merge
  ↓
Deployment
```

I treat implementation, testing, integration, and deployment as one end-to-end development process.

---

# Projects

## Spotidisk

**Repository:** `spotidisk`

### Target User

DJs who curate their music library through Spotify.

### Purpose

A desktop app for DJs who organize their music on Spotify and need the corresponding tracks available as local audio files.

### Architecture

Desktop application with Electron and a Python backend.

- **Desktop shell:** Electron
- **Frontend:** React / TypeScript
- **Backend:** Python / FastAPI
- **Communication:** WebSockets / OpenAPI
- **Async processing:** Python asyncio job system
- **Persistence:** local JSON
- **External sources:** Spotify for playlist metadata, YouTube for audio sourcing
- **Core:** process orchestration, async download jobs, and filesystem operations

### Technologies

- Electron
- React / TypeScript
- Python / FastAPI
- WebSockets / OpenAPI
- Playwright
- Asyncio
- JSON / filesystem APIs

---

## MultiBot — AI Chat Application

![Chatbot](https://github.com/user-attachments/assets/94795431-d852-4f5d-a75b-4887dd9fc032)

**Repository:** `test-multibot-app`

### Target User

Users who want richer, task-specific AI experiences than a traditional text-only chat.

### Purpose

An AI chat app designed to go beyond text responses by letting the AI create interactive interfaces such as charts, forms, and other task-specific UI.

### Architecture

Full-stack web application.

- **Frontend:** React / Vite / TanStack Router / React Query
- **Backend:** Node.js / TypeScript
- **API:** typed API layer
- **Database:** PostgreSQL / Drizzle
- **AI:** OpenAI / Vercel AI SDK
- **Features:** persistent conversations, auth middleware, background jobs, task queues, cron, tool calling, streaming, and LLM-generated UI.

### LLM Tool-Calling Flow

```text
User message → LLM → Tool call → Tool execution
                         ↓
                    Tool result
                         ↓
                        LLM
                         ↓
                  Final response
```

Multiple tools can execute concurrently while individual failures are handled independently.

---

## eBay / Funko Price Analytics

![BI Market](https://github.com/user-attachments/assets/61664291-78f0-4642-9c2c-8b606cc9b824)

![BI Market](https://github.com/user-attachments/assets/5567af50-ac79-463d-a3ec-03c1ede3fe30)

**Repository:** `test-ebay-price-items-sold--funko`

### Target User

Collectors and users interested in the Funko secondary market.

### Purpose

A data-analysis app for understanding Funko resale prices by exploring historical eBay sales, prices, and trends.

### Architecture

Full-stack web application with an external data pipeline.

- **Frontend:** React / TypeScript, DataStore, indexes, caching, tables, charts
- **Backend / API:** authenticated typed API
- **Data pipeline:** eBay → Google Sheets → n8n → API
- **Storage:** Google Sheets

---

## shadcn-registry-ts

![shadcn-registry-ts](https://github.com/user-attachments/assets/bb6af0c0-84ad-46a8-9402-012881752ff7)

**Repository:** `shadcn-registry-ts`

### Purpose

A developer-focused library for discovering and adding reusable TypeScript utilities through the shadcn registry model.

### Architecture

Client-side TypeScript package with no backend or database.

- **Distribution:** shadcn-compatible registry
- **Model:** source code is added directly to the developer's project

---

## Figma — Duplicate Color Styles

![Figma Duplicate Color Styles](https://github.com/user-attachments/assets/2e700987-74ad-46a8-9402-012881752ff7)

**Repository:** `figma-plugins`

### Target User

Designers working with Figma Color Styles.

### Purpose

A Figma plugin that lets designers duplicate an entire Color Style folder in one action instead of recreating the styles manually.

### Architecture

Client-only Figma plugin.

- **Runtime:** Figma Plugin API
- **UI:** plugin UI
- **Core:** reads, duplicates, and organizes Color Styles entirely inside Figma

---

## Gradia

![Gradia](https://user-images.githubusercontent.com/47954700/213765289-fdaad04a-906b-4361-8c78-1709f357a131.png)

**Repository:** `gradientor`

### Target User

Developers and designers who create CSS gradients.

### Purpose

A visual CSS gradient generator that lets developers and designers build complex gradients visually and copy the resulting CSS.

### Architecture

Client-only SPA with no backend or database.

- **Frontend:** web UI
- **Core:** client-side gradient state → CSS / CSS-in-JS output

---

# Additional Technical Experience

### Business Intelligence

- Google Sheets / Apps Script
- Data collection and transformation
- Statistical calculations
- Data visualization

### Automation

- n8n
- Scheduled workflows
- API integrations
- Data pipelines

### CMS

- WordPress / Advanced Custom Fields / Bricks
- Custom CSS

### UI & Design Tools

- Figma plugin development
- Component libraries / design systems
- Complex interactive interfaces
- Data visualization

### Developer Tools

- TypeScript utilities
- shadcn registries
- AI developer tools
- Internal productivity tools

---

## Core Skills

### Frontend

- TypeScript / JavaScript
- React / Next.js
- TanStack Router / React Query / Table / Virtual
- Svelte / SvelteKit
- Tailwind CSS
- shadcn/ui / Base UI / Radix UI / Chakra UI
- Complex tables, filtering, sorting, and data visualization
- Client-side state, data stores, Markdown and AI rendering
- PWA development
- Typed API integration

### Backend

- Node.js / TypeScript
- Python / FastAPI
- Express
- REST / OpenAPI
- tRPC / oRPC / ts-rest
- Contract-first API design
- PostgreSQL / MySQL / SQLite
- Drizzle / Prisma / Supabase
- Zod
- Async programming
- Background jobs / task queues
- WebSockets
- Filesystem-based applications

### AI / LLM

- OpenAI APIs / Vercel AI SDK
- LLM tool calling and function execution
- Multi-chatbot architectures
- Tool schemas and structured inputs
- Streaming AI interfaces
- External API tools
- Conversation persistence
- AI-powered UX
- LLM-generated UI

### Architecture

- Full-stack application architecture
- UI / API / business-logic separation
- Domain-oriented backend services
- Typed API contracts and generated clients
- Authentication / middleware
- Async jobs and cron processing
- Client-side indexing and caching
- Desktop architecture and process orchestration

### Testing & Reliability

- Unit / integration / API / service testing
- End-to-end and real-system E2E testing
- Async / concurrency debugging
- Performance instrumentation
- Error handling and logging

### Tooling & Automation

- Vite / TanStack
- pnpm / npm
- Git / GitHub
- Docker
- Electron / esbuild
- n8n
- Google Apps Script / Google Sheets
- Figma plugin development

---

# Open Source Contributions

### ESLint

Documentation upgrade.

https://github.com/eslint/eslint/pull/19297

### Local — Note Addon

Added an edit feature to the Local "Note" addon.

https://github.com/getflywheel/local-addon-notes/pull/29

### Chakra UI

Documentation upgrade.

https://github.com/chakra-ui/chakra-ui-docs/pull/1062

---

# What I Bring to a Team

- End-to-end feature ownership
- Strong TypeScript / React experience
- Full-stack flexibility
- AI application development
- Data-oriented engineering
- Backend and API design
- Testing mindset
- Product / UX thinking
- Ability to work across unfamiliar technologies
- Experience taking products from idea to deployment
