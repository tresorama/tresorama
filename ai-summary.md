# Developer Profile

## Full-Stack Product Developer

Full-stack product developer and software builder with a strong TypeScript/React background and hands-on experience building AI-powered applications, data-heavy interfaces, typed APIs, asynchronous systems, automated tests, databases, automation workflows, developer tools, and desktop software.

I am a builder-oriented developer: I am comfortable taking an idea or ambiguous requirement, making architectural decisions, implementing the product end-to-end, and getting it into a working, deployable state. My experience spans frontend, backend, data, AI, and infrastructure rather than being limited to a single layer of the stack.

I enjoy taking ambiguous product requirements and turning them into working systems, with particular interest in the intersection of product development, backend engineering, data, and AI.

---

## Builder Mindset

**Product-oriented, end-to-end software builder.**

I am comfortable taking an idea or ambiguous requirement and turning it into a working, deployable product.

My approach typically covers the full development cycle:

**Product → Architecture → Implementation → Integration → Testing → Debugging → Deployment**

### What distinguishes my approach

- **UX-first product thinking** — I usually start from the user interface and the experience I want the user to have. I think about how the product should present information, guide actions, and reduce friction before deciding how the backend, data model, APIs, or infrastructure should work. I then derive the technical architecture from those product and UX requirements.
- **End-to-end ownership** — I can work across frontend, backend, data, AI, integrations, testing, and deployment rather than being limited to a single layer.
- **Cross-domain** — I have built web applications, data platforms, AI applications, desktop software, developer tools, and Figma plugins.
- **Technology-independent** — I am comfortable entering unfamiliar technical domains and learning the technologies required to build the product.
- **Systems thinking** — I consider data flow, APIs, persistence, asynchronous processing, reliability, testing, and operational concerns as part of the product.
- **Build-first mindset** — I prefer turning ideas into working software and learning through implementation rather than limiting exploration to prototypes or technical specifications.

---

## Core Skills

### Frontend

- TypeScript / JavaScript
- React
- Next.js
- TanStack ecosystem
- TanStack Router / React Query / TanStack Table / TanStack Virtual
- Svelte / SvelteKit
- Tailwind CSS
- shadcn/ui / Base UI / Radix UI / Chakra UI
- Complex tables, filtering, sorting, and data visualization
- Client-side state and data stores
- Markdown and AI response rendering
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
- Asynchronous programming
- Background jobs and task queues
- WebSockets
- Filesystem-based applications

### AI / LLM Applications

- OpenAI APIs
- Vercel AI SDK
- LLM tool calling
- Function and tool execution
- Multi-chatbot architectures
- Tool schemas and structured inputs
- Streaming AI interfaces
- External API tools
- Conversation persistence
- AI-powered UX
- LLM-generated UI and renderable responses

### Architecture

- Full-stack application architecture
- Separation of UI, API, and business logic
- Domain-oriented backend services
- Typed API contracts
- Generated API clients
- Authentication and middleware
- Async jobs
- Cron / scheduled processing
- Client-side indexing and caching
- Desktop application architecture
- Process orchestration

### Testing & Reliability

- Unit testing
- Integration testing
- API testing
- Service-level testing
- End-to-end testing
- Real-system E2E testing
- Async / concurrency debugging
- Performance instrumentation
- Error handling and logging

### Tooling & Automation

- Vite
- TanStack
- pnpm / npm
- Git / GitHub
- Docker
- Electron
- esbuild
- n8n
- Google Apps Script
- Google Sheets
- Figma plugin development

---

## Development Workflow

```
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

I prefer an end-to-end workflow where implementation, testing, integration, and deployment are treated as parts of the same development process.

---

# Projects

## MultiBot — AI Chat Application

![Chatbot](https://github.com/user-attachments/assets/94795431-d852-4f5d-a75b-4887dd9fc032)

**Repository:** `test-multibot-app`

### Target User

Users who want to interact with AI through richer, task-specific experiences than a traditional text-only chat.

### Purpose

A chat experience that goes beyond traditional text-based AI by allowing the LLM to generate interactive UI components inside the conversation.

### Architecture

Full-stack web application.

- **Frontend:** React / Vite / TanStack Router / TanStack React Query
- **Backend:** Node.js / TypeScript
- **API:** typed API layer
- **Database:** PostgreSQL / Drizzle
- **AI:** OpenAI / Vercel AI SDK
- **Architecture:** persistent conversations, authentication middleware, background jobs, task queues, cron processing, tool calling, streaming responses, and LLM-generated interactive UI.

### LLM Tool-Calling Flow

```
User message
     ↓
    LLM
     ↓
 Tool call
     ↓
Tool execution
     ↓
Tool result
     ↓
    LLM
     ↓
Final response
```

The tool layer can execute multiple calls concurrently while handling individual tool failures independently.

### Technologies

- React / Vite
- TanStack Router
- TanStack React Query
- Node.js / TypeScript
- PostgreSQL
- Drizzle
- Tailwind CSS
- OpenAI
- Vercel AI SDK
- Typed API layers

---

## eBay / Funko Price Analytics

![BI Market](https://github.com/user-attachments/assets/61664291-78f0-4642-9c2c-8b606cc9b824)

![BI Market](https://github.com/user-attachments/assets/5567af50-ac79-463d-a3ec-03c1ede3fe30)

**Repository:** `test-ebay-price-items-sold--funko`

### Target User

Collectors and users interested in analyzing the Funko secondary market.

### Purpose

An application for analyzing a specific secondary market through historical sales data, interactive tables, filters, statistics, and visualizations.

### Architecture

Full-stack web application with a data-analysis frontend and an external data pipeline.

- **Frontend:** React / TypeScript with a client-side DataStore, indexes, caching, interactive tables, and charts
- **Backend / API:** authenticated typed API
- **Data pipeline:** eBay → Google Sheets → n8n → API
- **Storage:** Google Sheets
- **Architecture:** data collection and transformation are handled by the pipeline, while the frontend maintains indexed and cached data for responsive filtering, aggregation, and visualization.

---

## Spotidisk

**Repository:** `spotidisk`

### Target User

DJs who curate their music library through Spotify.

### Purpose

A desktop application that turns a DJ's Spotify playlist workflow into a local audio-library workflow, with download progress and job cancellation.

### Architecture

Desktop application composed of an Electron frontend/orchestrator and a Python backend.

- **Desktop shell:** Electron
- **Frontend:** React / TypeScript
- **Backend:** Python / FastAPI
- **Communication:** WebSockets / OpenAPI
- **Async processing:** Python asyncio job system
- **Persistence:** local JSON file
- **External sources:** Spotify for playlist metadata and YouTube for audio sourcing
- **Architecture:** Electron launches and manages the application processes; the React UI communicates with the FastAPI backend, which handles asynchronous download jobs and filesystem operations.

### Technologies

- Electron
- React / TypeScript
- Python
- FastAPI
- WebSockets
- Playwright
- OpenAPI
- Asyncio
- JSON-based local persistence
- Filesystem APIs

---

## shadcn-registry-ts

![shadcn-registry-ts](https://github.com/user-attachments/assets/bb6af0c0-84cd-4841-b2f0-f3e7d1acd672)

**Repository:** `shadcn-registry-ts`

### Purpose

A small developer-focused library that provides reusable TypeScript utilities through the shadcn registry model, making the utilities easy to discover and add to projects.

### Architecture

Client-side developer library / registry package. No backend or database.

- **Runtime:** TypeScript
- **Distribution:** shadcn-compatible registry
- **Architecture:** reusable TypeScript utilities are exposed through the registry so developers can add the source code directly to their projects.

---

## Figma — Duplicate Color Styles

![Figma Duplicate Color Styles](https://github.com/user-attachments/assets/2e700987-74ad-46a8-9402-012881752ff7)

**Repository:** `figma-plugins`

### Target User

Designers working with Figma Color Styles.

### Purpose

A Figma plugin that removes a repetitive manual operation by duplicating an entire Color Style folder in one action.

### Architecture

Client-only Figma plugin. No external backend or database.

- **Runtime:** Figma Plugin API
- **UI:** plugin UI
- **Architecture:** the plugin reads Color Style folders through the Figma API, duplicates the styles, and creates a new folder entirely within the Figma environment.

---

## Gradia

![Gradia](https://user-images.githubusercontent.com/47954700/213765289-fdaad04a-906b-4361-8c78-1709f357a131.png)

**Repository:** `gradientor`

### Target User

Developers and designers who need to create CSS gradients.

### Purpose

A visual tool that solves the practical problem of creating complex multi-layer CSS gradients without manually constructing the CSS.

### Architecture

Client-only frontend application / SPA. No backend or database.

- **Frontend:** web UI
- **Architecture:** gradient configuration is maintained in client-side state and transformed directly into CSS / CSS-in-JS output. All editing and generation happen in the browser.

---

# Additional Technical Experience

### Business Intelligence

- Google Sheets
- Google Apps Script
- Data collection and transformation
- Statistical calculations
- Data visualization

### Automation

- n8n
- Scheduled workflows
- API integrations
- Data pipelines

### CMS

- WordPress
- Advanced Custom Fields
- Bricks
- Custom CSS

### UI & Design Tools

- Figma plugin development
- Component libraries
- Design systems
- Complex interactive interfaces
- Data visualization

### Developer Tools

- TypeScript utilities
- shadcn registries
- AI developer tools
- Internal productivity tools

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

- End-to-end ownership of features
- Strong full-stack flexibility
- Strong TypeScript / React experience
- Hands-on AI application development
- Data-oriented engineering
- Backend engineering
- API and contract design
- Testing mindset
- Product-oriented thinking
- Ability to work across unfamiliar technologies
- Experience taking projects from idea to deployment

---

# Current Focus

I am currently focusing on deeper backend and systems engineering topics:

- Database internals
- Indexes and query optimization
- `EXPLAIN`
- Transactions
- Async and concurrent systems
- Queues and distributed processing
- LLM agent architectures
- Tool systems
- Observability
- Reliability
- System design

---

# Profile Summary

Full-stack product developer with a strong TypeScript/React background and hands-on experience building AI-powered applications, data-heavy interfaces, typed APIs, asynchronous systems, automated tests, databases, automation workflows, developer tools, and desktop software.

I enjoy taking ambiguous product requirements and turning them into working systems, with particular interest in the intersection of product development, backend engineering, data, and AI.
