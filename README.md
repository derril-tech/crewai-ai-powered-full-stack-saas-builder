# 🚀 AI-Powered Full-Stack SaaS Builder
**Powered by CrewAI + OpenAI**

🌐 **[View Live Application](https://crewai-ai-powered-full-stack-saas-builder-cyan.vercel.app/)**

> **Transform a high-level SaaS idea into a production-ready full-stack starter in minutes. AI agents design your database, plan your API, craft your UI, and generate complete Next.js applications—all orchestrated seamlessly.** ⚡

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.11+-blue.svg)](https://www.python.org/downloads/)
[![Next.js](https://img.shields.io/badge/Next.js-16-black.svg)](https://nextjs.org/)
[![React](https://img.shields.io/badge/React-19.2-61DAFB.svg)](https://react.dev/)
[![CrewAI](https://img.shields.io/badge/CrewAI-AI_Agents-purple.svg)](https://www.crewai.com/)
[![Railway](https://img.shields.io/badge/Deploy-Railway-blueviolet.svg)](https://railway.app/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-black.svg)](https://vercel.com/)

---

## ✨ What It Does

This Builder Studio uses a **multi-agent CrewAI workflow** to transform SaaS ideas into complete applications:

1. **Architect Designs** — Creates database schemas, API routes, and system architecture using GPT-4o-mini
2. **Backend Dev Refines** — Validates RESTful APIs, normalizes databases, and adds production best practices
3. **Frontend Dev Crafts** — Designs Next.js pages, React components, and modern UI/UX patterns
4. **QA Validates** — Ensures schema correctness, security, and production readiness

The result? A complete, downloadable SaaS starter with database migrations, API routes, authentication, billing integration, and a beautiful UI—all generated from a simple idea.

---

## 🎯 Core Features

### 🤖 **AI-Powered Planning & Generation**
- **Multi-Agent Orchestration** — CrewAI coordinates 4 specialized agents (Architect, Backend, Frontend, QA)
- **Intelligent Planning** — Generates comprehensive plans with data models, API routes, and UI structure in 3-4 minutes
- **Code Generation** — Produces production-ready Next.js applications with TypeScript, Tailwind, and shadcn/ui
- **AI Feature Suggestions** — Get AI-powered recommendations during project creation to enhance your SaaS idea
- **Template Gallery** — Start from 9 pre-built templates (Subscription Analytics, CRM, E-commerce, Content Management, Project Management, Email Marketing, Learning Management, Help Desk, and more)
- **TODO Implementation** — Automatically implement TODO comments in generated code using AI

### 🗄️ **Database Architecture**
- **Schema Design** — AI generates normalized PostgreSQL schemas with proper relationships
- **Migration Scripts** — Ready-to-run SQL migrations for Supabase or any PostgreSQL database
- **Data Modeling** — Intelligent entity identification with foreign keys, indexes, and constraints
- **Audit Fields** — Automatic inclusion of created_at, updated_at, and soft delete patterns

### 🔌 **API Design & Implementation**
- **RESTful Architecture** — AI designs complete API routes following industry best practices
- **FastAPI Backend** — Generated endpoints with proper validation, error handling, and documentation
- **Authentication** — Org-based auth patterns with NextAuth integration
- **Billing Integration** — Stripe webhook handlers and subscription management

### 🎨 **Modern UI/UX**
- **Next.js 16 App Router** — Latest React Server Components and streaming
- **React 19.2** — Cutting-edge React features with optimized performance
- **Fully Responsive** — Mobile-first design with 44px+ touch targets, optimized for all screen sizes
- **Dark/Light Mode** — Beautiful theming with system preference support and lighter borders in dark theme
- **Component Library** — shadcn/ui components with Tailwind CSS
- **Form Validation** — Real-time validation with helpful toast notifications
- **Duplicate Prevention** — Automatic checking for duplicate project titles

### 📦 **Complete Application Scaffolding**
- **File Tree Explorer** — Browse generated code structure with syntax highlighting
- **Diff Viewer** — View file contents with TODO highlighting and one-click implementation
- **Copy File** — Copy entire file contents to clipboard with one click
- **ZIP Downloads** — Download complete SaaS starters as ready-to-deploy packages
- **Artifact Management** — Delete and download artifacts directly from the UI
- **Run Comparison** — Compare different generations to see improvements
- **Real-Time Progress** — Live updates during plan and code generation with progress indicators

### 💳 **Billing & Subscriptions**
- **Stripe Integration** — Test mode billing with webhook support
- **Subscription Management** — Customer and subscription tracking
- **Org-Based Billing** — Multi-tenant billing status per organization

---

## 🏗️ Tech Stack

### **Frontend** ⚛️
| Technology | Purpose |
|------------|---------|
| **Next.js 16** | React framework with App Router |
| **React 19.2** | Latest React with Server Components |
| **TypeScript** | Type-safe development |
| **Tailwind CSS** | Utility-first styling |
| **shadcn/ui** | Beautiful component library |
| **next-themes** | Dark/light mode management |

### **Backend** 🐍
| Technology | Purpose |
|------------|---------|
| **FastAPI** | High-performance Python API |
| **CrewAI** | Multi-agent AI orchestration |
| **OpenAI GPT-4o-mini** | Intelligent planning and generation (optimized for speed and cost) |
| **Pydantic v2** | Data validation and serialization |
| **Uvicorn** | ASGI server for production |

### **Data & Infrastructure** 💾
| Technology | Purpose |
|------------|---------|
| **Supabase** | PostgreSQL database with RPC functions |
| **Upstash Redis** | Job queue, caching, and rate limiting |
| **Stripe** | Payment processing and subscriptions |

### **Deployment** 🚀
| Platform | Service |
|----------|---------|
| **Vercel** | Frontend hosting with edge functions |
| **Railway** | Backend API deployment |

---

## 🔄 How It Works

```
┌─────────────────────────────────────────────────────────────┐
│                    USER INPUT                               │
│         SaaS Idea + Project Title (optional template)        │
└─────────────────────┬───────────────────────────────────────┘
                      │
                      ▼
┌─────────────────────────────────────────────────────────────┐
│                 CREWAI MULTI-AGENT WORKFLOW                 │
│  ┌──────────────┐  ┌──────────────┐  ┌──────────────┐      │
│  │  Architect   │──│   Backend    │──│   Frontend   │      │
│  │   Designs    │  │    Refines   │  │    Crafts    │      │
│  │  (GPT-4o-mini)│  │ (GPT-4o-mini)│  │(GPT-4o-mini)│      │
│  └──────────────┘  └──────────────┘  └──────┬───────┘      │
│                                             │               │
│                                    ┌────────▼────────┐      │
│                                    │   QA Validates   │      │
│                                    │   (GPT-4o-mini)  │      │
│                                    └────────┬────────┘      │
└─────────────────────────────────────────────┼───────────────┘
                                              │
                                              ▼
┌─────────────────────────────────────────────────────────────┐
│                    GENERATED OUTPUT                         │
│  • Database Schema (PostgreSQL migrations)                  │
│  • API Routes (FastAPI endpoints)                           │
│  • UI Pages (Next.js App Router)                            │
│  • React Components (TypeScript + Tailwind)                 │
│  • Authentication (Org-based auth)                          │
│  • Billing Integration (Stripe webhooks)                   │
│  • Complete File Structure (120+ files)                    │
│  • TODO Comments (with AI implementation support)          │
└─────────────────────────────────────────────────────────────┘
```

---

## 🎯 Key Capabilities Demonstrated

### **End-to-End Product Development**
This project showcases comprehensive understanding of full-stack development:

- **Database Design** — From entity identification to normalized schemas with proper relationships, indexes, and constraints
- **API Architecture** — RESTful design with validation, error handling, authentication, and documentation
- **UI/UX Design** — Modern, responsive interfaces with accessibility, theming, and smooth user experiences
- **Authentication Systems** — Org-based multi-tenant authentication with secure session management
- **AI Integration** — Sophisticated multi-agent orchestration for intelligent planning and code generation
- **Mobile Optimization** — Fully responsive design with proper touch targets and mobile-first layouts

### **Production-Ready Architecture**
- **Scalable Backend** — FastAPI with async/await, proper error handling, and rate limiting
- **Resilient Data Layer** — Supabase with RPC functions for secure access, Redis for caching and job queues
- **Modern Frontend** — Next.js 16 with React 19.2, optimized bundles, and server-side rendering
- **Cloud Deployment** — Railway for backend, Vercel for frontend with proper environment management
- **Performance Optimized** — Plan generation optimized to 3-4 minutes using GPT-4o-mini

### **Developer Experience**
- **Type Safety** — TypeScript throughout, Pydantic models for validation
- **Component Reusability** — Modular architecture with shared components and utilities
- **Error Handling** — Comprehensive error boundaries, fallbacks, and user-friendly messages
- **Observability** — Job tracking, logging, and real-time status updates
- **Code Quality** — TODO detection and AI-powered implementation assistance

---

## 📸 Application Flow

### 🏠 **Landing Page**
*Elegant hero section with video background showcasing the AI-powered builder*

### 🎨 **Studio Dashboard**
*Project management interface with real-time statistics, project listings, and template gallery*

### 🚀 **Project Creation**
*Create new projects with AI feature suggestions, form validation, and duplicate title checking*

### 📋 **Plan Generation**
*Interactive plan generation with real-time progress updates and structured plan preview*

### 💻 **Code Generation**
*Generate complete Next.js applications with file tree navigation and artifact management*

### 📁 **Code Explorer**
*File tree navigation with syntax-highlighted code diffs, TODO highlighting, and one-click implementation*

### 🔄 **Run Comparison**
*Side-by-side comparison of different code generations to track improvements*

---


## 📖 User Guide

### Getting Started

1. **Sign In** — Create an account and join/create an organization
2. **Create Project** — Start a new Builder Project with your SaaS idea or choose from 9 pre-built templates
3. **Get AI Suggestions** — Receive AI-powered feature suggestions to enhance your idea (available during project creation)
4. **Generate Plan** — Let AI design your database, API, and UI structure (takes 3-4 minutes)
5. **Review Plan** — Explore the generated architecture with interactive preview
6. **Generate Code** — Create the complete Next.js application
7. **Explore & Download** — Browse files, view diffs, implement TODOs, and download ZIP

### Understanding Your Generated Plan

| Section | What It Contains |
|---------|------------------|
| **Data Model** | Database tables with columns, types, relationships, and indexes |
| **API Routes** | RESTful endpoints with methods, paths, and summaries |
| **UI Pages** | Next.js routes with page names and component lists |
| **UI Components** | React components with props and functionality |
| **Billing** | Stripe integration configuration and webhook events |
| **Generation** | Required files and file budget constraints |

### Working with Generated Code

- **File Tree** — Navigate through all generated files with a searchable tree view
- **Diff Viewer** — View file contents with syntax highlighting
- **TODO Detection** — Automatically highlights TODO comments in yellow
- **Implement TODOs** — Click "Implement" next to any TODO to generate replacement code using AI
- **Copy Files** — Copy entire file contents to clipboard with one click
- **Download Artifacts** — Download ZIP files or individual artifacts
- **Delete Artifacts** — Remove unwanted artifacts from your runs

### Pro Tips

- **Be Specific** — Detailed ideas lead to better, more complete plans
- **Use Templates** — Start from one of 9 pre-built templates for faster setup
- **Get Suggestions** — Use AI feature suggestions during project creation to enhance your idea
- **Review Plans** — Carefully review the generated plan before code generation
- **Compare Runs** — Generate multiple versions to see different approaches
- **Implement TODOs** — Use the TODO implementation feature to complete generated code

---

## 📊 Performance & Quality

| Metric | Value |
|--------|-------|
| Plan Generation | ~3-4 minutes (optimized) |
| Code Generation | ~60-120 seconds |
| Frontend Bundle | Optimized with Next.js |
| Mobile Ready | ✅ Yes (44px+ touch targets, fully responsive) |
| Type Safety | ✅ Full TypeScript coverage |
| Error Handling | ✅ Comprehensive with fallbacks |
| AI Model | GPT-4o-mini (optimized for speed and cost) |

---

## 🛡️ Security & Best Practices

- ✅ **Secure Database Access** — RPC functions prevent schema exposure
- ✅ **API Rate Limiting** — Redis-based rate limiting per organization
- ✅ **Input Validation** — Pydantic models and TypeScript types
- ✅ **Environment Variables** — All secrets in environment, never committed
- ✅ **CORS Protection** — Configured for production domains
- ✅ **Error Sanitization** — User-friendly error messages without sensitive data
- ✅ **Duplicate Prevention** — Automatic checking for duplicate project titles
- ✅ **Form Validation** — Client and server-side validation with helpful feedback

---

## 🎨 Architecture Highlights

### **Multi-Agent AI System**
The application demonstrates sophisticated AI orchestration:
- **Sequential Processing** — Agents work in sequence, each building on previous output
- **Context Passing** — Each agent receives full context from previous agents
- **Validation Layer** — QA agent ensures production readiness before final output
- **Optimized Prompts** — Carefully crafted prompts for each agent role
- **Speed Optimization** — Using GPT-4o-mini for faster, cost-effective generation

### **Resilient Data Layer**
- **Dual Storage** — Redis for speed, Supabase for persistence
- **Job Tracking** — Automatic fallback from Redis to Supabase
- **RPC Functions** — Secure database access without schema exposure
- **Schema Isolation** — Custom schema per project for multi-tenancy

### **Modern Frontend Architecture**
- **Server Components** — Next.js 16 App Router with React Server Components
- **State Management** — React hooks with optimistic updates
- **Real-Time Updates** — Polling and job status tracking
- **Component Architecture** — Reusable, typed components with shadcn/ui
- **Mobile-First Design** — Responsive layouts with proper touch targets and breakpoints

### **Code Generation Features**
- **Dynamic Generation** — Files generated from plan specifications
- **Missing File Handling** — Automatic stub generation for required files
- **TODO Support** — AI-powered TODO implementation
- **Artifact Management** — Full CRUD operations for generated artifacts
- **File Operations** — Copy, download, and view operations for all files

---

## 👨‍💻 Creator

**Derril Filemon**

This project demonstrates proficiency in:

- 🤖 **AI/ML Integration** — CrewAI multi-agent workflows, OpenAI GPT-4o-mini
- ⚛️ **Modern React** — Next.js 16, React 19.2, Server Components, App Router
- 🐍 **Python Backend** — FastAPI, async/await, Pydantic v2, type safety
- 🗄️ **Database Design** — PostgreSQL, schema design, RPC functions, migrations
- 🎨 **UI/UX Design** — Responsive design, accessibility, dark mode, animations, mobile optimization
- ☁️ **Cloud Architecture** — Supabase, Redis, Railway, Vercel, environment management
- 🔧 **DevOps** — Monorepo management, CI/CD, deployment automation
- 🔐 **Security** — Authentication, authorization, secure API design, input validation
- 📦 **Code Generation** — File system operations, template rendering, artifact creation, TODO implementation

---

## 🙏 Acknowledgments

- **[CrewAI](https://www.crewai.com/)** — Multi-agent orchestration framework
- **[OpenAI](https://openai.com/)** — GPT-4o-mini API for intelligent planning
- **[Supabase](https://supabase.com/)** — PostgreSQL database and RPC functions
- **[Upstash](https://upstash.com/)** — Redis caching and job queues
- **[Railway](https://railway.app/)** — Backend API deployment
- **[Vercel](https://vercel.com/)** — Frontend hosting and edge functions
- **[shadcn/ui](https://ui.shadcn.com/)** — Beautiful, accessible components
- **[Stripe](https://stripe.com/)** — Payment processing and subscriptions

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

<div align="center">

[Live Demo](https://crewai-ai-powered-full-stack-saas-builder-cyan.vercel.app/) 

Made with ❤️ and ☕ by [Derril Filemon](https://github.com/derril-tech)

</div>
