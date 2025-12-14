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

1. **Architect Designs** — Creates database schemas, API routes, and system architecture using GPT-4.1-mini
2. **Backend Dev Refines** — Validates RESTful APIs, normalizes databases, and adds production best practices
3. **Frontend Dev Crafts** — Designs Next.js pages, React components, and modern UI/UX patterns
4. **QA Validates** — Ensures schema correctness, security, and production readiness

The result? A complete, downloadable SaaS starter with database migrations, API routes, authentication, billing integration, and a beautiful UI—all generated from a simple idea.

---

## 🎯 Core Features

### 🤖 **AI-Powered Planning & Generation**
- **Multi-Agent Orchestration** — CrewAI coordinates 4 specialized agents (Architect, Backend, Frontend, QA)
- **Intelligent Planning** — Generates comprehensive plans with data models, API routes, and UI structure
- **Code Generation** — Produces production-ready Next.js applications with TypeScript, Tailwind, and shadcn/ui
- **Real-Time Suggestions** — AI-powered recommendations to enhance your SaaS idea

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
- **Responsive Design** — Mobile-first approach with 44px+ touch targets
- **Dark/Light Mode** — Beautiful theming with system preference support
- **Component Library** — shadcn/ui components with Tailwind CSS

### 📦 **Complete Application Scaffolding**
- **File Tree Explorer** — Browse generated code structure with syntax highlighting
- **Diff Viewer** — Side-by-side comparison of generated files
- **ZIP Downloads** — Download complete SaaS starters as ready-to-deploy packages
- **Run Comparison** — Compare different generations to see improvements
- **Shareable Links** — Generate public read-only links for sharing projects

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
| **OpenAI GPT-4.1-mini** | Intelligent planning and generation |
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

## 🎯 Key Capabilities Demonstrated

### **End-to-End Product Development**
This project showcases comprehensive understanding of full-stack development:

- **Database Design** — From entity identification to normalized schemas with proper relationships, indexes, and constraints
- **API Architecture** — RESTful design with validation, error handling, authentication, and documentation
- **UI/UX Design** — Modern, responsive interfaces with accessibility, theming, and smooth user experiences
- **Authentication Systems** — Org-based multi-tenant authentication with secure session management
- **AI Integration** — Sophisticated multi-agent orchestration for intelligent planning and code generation

### **Production-Ready Architecture**
- **Scalable Backend** — FastAPI with async/await, proper error handling, and rate limiting
- **Resilient Data Layer** — Supabase with RPC functions for secure access, Redis for caching and job queues
- **Modern Frontend** — Next.js 16 with React 19.2, optimized bundles, and server-side rendering
- **Cloud Deployment** — Railway for backend, Vercel for frontend with proper environment management

### **Developer Experience**
- **Type Safety** — TypeScript throughout, Pydantic models for validation
- **Component Reusability** — Modular architecture with shared components and utilities
- **Error Handling** — Comprehensive error boundaries, fallbacks, and user-friendly messages
- **Observability** — Job tracking, logging, and real-time status updates

---

## 📸 Application Flow

### 🏠 **Landing Page**
*Elegant hero section with video background showcasing the AI-powered builder*

### 🎨 **Studio Dashboard**
*Project management interface with real-time statistics and project listings*

### 🚀 **Project Builder**
*Interactive plan generation with AI suggestions and structured plan preview*

### 📁 **Code Explorer**
*File tree navigation with syntax-highlighted code diffs and ZIP downloads*

### 🔄 **Run Comparison**
*Side-by-side comparison of different code generations to track improvements*

---

## 📖 User Guide

### Getting Started

1. **Sign In** — Create an account and join/create an organization
2. **Create Project** — Start a new Builder Project with your SaaS idea
3. **Generate Plan** — Let AI design your database, API, and UI structure
4. **Review Plan** — Explore the generated architecture with interactive preview
5. **Generate Code** — Create the complete Next.js application
6. **Explore & Download** — Browse files, view diffs, and download ZIP

### Understanding Your Generated Plan

| Section | What It Contains |
|---------|------------------|
| **Data Model** | Database tables with columns, types, relationships, and indexes |
| **API Routes** | RESTful endpoints with methods, paths, and summaries |
| **UI Pages** | Next.js routes with page names and component lists |
| **Billing** | Stripe integration configuration and webhook events |
| **Generation** | Required files and file budget constraints |

### Pro Tips

- **Be Specific** — Detailed ideas lead to better, more complete plans
- **Use Constraints** — Specify preferences like "use Prisma" or "include analytics"
- **Review Plans** — Use AI suggestions to refine your architecture before generating
- **Compare Runs** — Generate multiple versions to see different approaches
- **Share Projects** — Generate shareable links for collaboration

---

## 📊 Performance & Quality

| Metric | Value |
|--------|-------|
| Plan Generation | ~30-60 seconds |
| Code Generation | ~60-120 seconds |
| Frontend Bundle | Optimized with Next.js |
| Mobile Ready | ✅ Yes (44px+ touch targets) |
| Type Safety | ✅ Full TypeScript coverage |
| Error Handling | ✅ Comprehensive with fallbacks |

---

## 🛡️ Security & Best Practices

- ✅ **Secure Database Access** — RPC functions prevent schema exposure
- ✅ **API Rate Limiting** — Redis-based rate limiting per organization
- ✅ **Input Validation** — Pydantic models and TypeScript types
- ✅ **Environment Variables** — All secrets in environment, never committed
- ✅ **CORS Protection** — Configured for production domains
- ✅ **Error Sanitization** — User-friendly error messages without sensitive data

---

## 🎨 Architecture Highlights

### **Multi-Agent AI System**
The application demonstrates sophisticated AI orchestration:
- **Sequential Processing** — Agents work in sequence, each building on previous output
- **Context Passing** — Each agent receives full context from previous agents
- **Validation Layer** — QA agent ensures production readiness before final output
- **Optimized Prompts** — Carefully crafted prompts for each agent role

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

---

## 👨‍💻 Creator

**Derril Filemon**

This project demonstrates proficiency in:

- 🤖 **AI/ML Integration** — CrewAI multi-agent workflows, OpenAI GPT-4.1-mini
- ⚛️ **Modern React** — Next.js 16, React 19.2, Server Components, App Router
- 🐍 **Python Backend** — FastAPI, async/await, Pydantic v2, type safety
- 🗄️ **Database Design** — PostgreSQL, schema design, RPC functions, migrations
- 🎨 **UI/UX Design** — Responsive design, accessibility, dark mode, animations
- ☁️ **Cloud Architecture** — Supabase, Redis, Railway, Vercel, environment management
- 🔧 **DevOps** — Monorepo management, CI/CD, deployment automation
- 🔐 **Security** — Authentication, authorization, secure API design, input validation
- 📦 **Code Generation** — File system operations, template rendering, artifact creation

---

## 🙏 Acknowledgments

- **[CrewAI](https://www.crewai.com/)** — Multi-agent orchestration framework
- **[OpenAI](https://openai.com/)** — GPT-4.1-mini API for intelligent planning
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
