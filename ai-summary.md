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

# Selected Projects

## MultiBot — AI Chat Application

**Repository:** `test-multibot-app`

A full-stack AI chat application exploring multiple chatbot architectures and LLM interaction patterns.

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

### Architecture

The application includes:

- Persistent conversations
- Authentication and authorization middleware
- Chat and LLM services
- Background jobs
- Task queues
- Scheduled / cron processing
- Tool calling
- Streaming AI responses
- Markdown rendering
- PWA support
- Service-level and database testing
- Logging and global error handling
- Resource monitoring

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

---

## eBay / Funko Price Analytics

**Repository:** `test-ebay-price-items-sold--funko`

A data-heavy application for analyzing historical sold-item prices for Funko products.

### Data Pipeline

```
eBay
  ↓
Data collection
  ↓
Google Sheets
  ↓
n8n
  ↓
API
  ↓
Frontend DataStore
  ↓
Indexes / Cache
  ↓
Tables + Charts
```

The application focuses heavily on data processing and frontend performance.

Features include:

- Historical price analysis
- Interactive tables
- Charts and visualizations
- Filtering
- Category / year / month / week indexes
- Cached expensive calculations
- Statistical computations
- Performance instrumentation
- Contract-first API
- Authenticated API access

### Screenshots

![BI Market](https://github.com/user-attachments/assets/61664291-78f0-4642-9c2c-8b606cc9b824)

![BI Market](https://github.com/user-attachments/assets/5567af50-ac79-463d-a3ec-03c1ede3fe30)

**Live demo:** https://test-ebay-price-items-sold-funko-sa.vercel.app/

---

## Spotidisk

**Repository:** `spotidisk`

A desktop application combining a React frontend with a Python/FastAPI backend.

### Technologies

- Electron
- React / TypeScript
- Python
- FastAPI
- WebSockets
- Playwright
- OpenAPI
- Asyncio
- Filesystem APIs

### Architecture

```
Electron
   ↓
React / TypeScript UI
   ↓
Python / FastAPI
   ↓
Async Job System
   ↓
External Music Providers
   ↓
Filesystem
```

The application includes asynchronous jobs, cancellation, WebSocket communication, process management, filesystem operations, packaging, and end-to-end testing.

The project also involved working deeply with Python's `asyncio`, task cancellation semantics, and desktop process orchestration.

---

# Additional Projects & Demos

## BI Market

Sale market tracking and statistical visualization.

The project is represented above by the `test-ebay-price-items-sold--funko` repository.

---

## Chatbot

ChatGPT-like chatbot with additional UI elements that can be rendered by the LLM.

The project is represented above by the `test-multibot-app` repository.

![Chatbot](https://github.com/user-attachments/assets/94795431-d852-4f5d-a75b-4887dd9fc032)

---

## shadcn-registry-ts

**Repository:** `shadcn-registry-ts`

A small library of TypeScript utilities distributed through a shadcn registry.

**Repository:** https://github.com/tresorama/shadcn-registry-ts

![shadcn-registry-ts](https://github.com/user-attachments/assets/bb6af0c0-84cd-4841-b2f0-f3e7d1acd672)

---

## Figma — Duplicate Color Styles

**Repository:** `figma-plugins`

A Figma plugin for duplicating a Color Style folder in one click.

The plugin allows the user to select the folder to duplicate and provide the name for the new folder.

**Repository:** https://github.com/tresorama/figma-plugins

![Figma Duplicate Color Styles](https://github.com/user-attachments/assets/2e700987-74ad-46a8-9402-012881752ff7)

---

## Gradia

**Repository:** `gradientor`

A visual tool for creating multi-layer CSS gradients and exporting them as pure CSS or CSS-in-JS.

**Repository:** https://github.com/tresorama/gradientor

![Gradia](https://user-images.githubusercontent.com/47954700/213765289-fdaad04a-906b-4361-8c78-1709f357a131.png)

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
