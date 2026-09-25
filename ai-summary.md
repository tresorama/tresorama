# Developer Profile

## Full-Stack Product Developer

Full-stack product developer with a strong TypeScript/React background and hands-on experience building AI-powered applications, data-heavy interfaces, typed APIs, asynchronous systems, automated tests, databases, automation workflows, developer tools, and desktop software.

I enjoy taking ambiguous product requirements and turning them into working systems, with particular interest in the intersection of product development, backend engineering, data, and AI.

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

### Purpose

A ChatGPT-like application where users can have persistent conversations with different AI chatbots. Its value compared with a standard ChatGPT-style chat is the ability for the LLM to produce new interactive UI experiences inside the conversation, guided by system prompts designed to improve the user experience. These include charts, video players, interactive forms, and other task-specific UI components.

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

### Purpose

A data-analysis application for users who want to track the secondary-market prices of Funko products and explore historical sales data through interactive tables, filters, statistics, and visualizations.

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

### Purpose

A desktop application targeted at DJs who curate their music library on Spotify and want to obtain the corresponding audio files on their local computer.

Users can process Spotify playlists and download their tracks to the local disk, using YouTube as the audio source. The application is designed to turn a playlist-based music collection managed on Spotify into a locally stored library of audio files.

The application also manages potentially long-running download operations, providing progress tracking and job cancellation.

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

### Purpose

A Figma plugin that lets designers duplicate an entire Color Style folder in one action, instead of manually recreating or copying the styles.

### Architecture

Client-only Figma plugin. No external backend or database.

- **Runtime:** Figma Plugin API
- **UI:** plugin UI
- **Architecture:** the plugin reads Color Style folders through the Figma API, duplicates the styles, and creates a new folder entirely within the Figma environment.
---

## Gradia

![Gradia](https://user-images.githubusercontent.com/47954700/213765289-fdaad04a-906b-4361-8c78-1709f357a131.png)

**Repository:** `gradientor`

### Purpose

A visual tool for creating complex multi-layer CSS gradients without having to manually construct the CSS. Users can visually compose gradient layers and export the resulting CSS or CSS-in-JS.

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
