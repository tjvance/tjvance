# Hi, I’m Tyler Vance

I build AI-enabled applications with a structured, strategy-aware approach that combines product thinking, system design, and disciplined implementation.

I’m interested in work where the challenge is a combination of building software and designing systemst that are:
- useful in real workflows
- trustworthy for users
- architecturally sound
- scoped and delivered in a repeatable way

My projects are meant to show how I think about:
- AI product development
- AI workflow design
- technical strategy
- human-in-the-loop systems
- implementation with modern tools like Codex, Claude, and incorporating new tools as they are made available to the public

---

## What I’m Focused On

I’m building applications and frameworks that sit at the intersection of:
- AI-enabled workflow automation
- product strategy
- software architecture
- technical delivery
- practical trust and approval boundaries

A core example is **SaidnDone**, an AI-powered meeting intelligence and follow-through application built around a staged workflow: upload meeting content, generate transcript/normalized text, create structured summary, extract structured action items, require review/approval, and then generate bounded draft outputs. That staged, review-first model is documented directly in the project’s product, architecture, and implementation files.

---

## My Development Framework

I use a planning-first framework for building applications with Codex and other AI coding tools.

Instead of treating AI as a shortcut, I treat it as an implementation accelerator inside a clearly defined system of:
- product scope
- architecture decisions
- vertical-slice delivery
- trust boundaries
- iterative review

The core repo files I use to run projects are:
- `README.md`
- `SPEC.md`
- `ARCHITECTURE.md`
- `AGENTS.md`
- `ROADMAP.md`
- `TASKS.md`
- `IMPLEMENTATION_APPROACH.md`
- `DECISIONS.md`
- `LESSONS_LEARNED.md`

That markdown-first operating model is the backbone of how I work with AI-powered coding agents: define the system first, then let the tool implement bounded slices of it.

---

## How I Build With AI-powered coding agents

For each feature or slice, I use a repeatable workflow:

1. define or update scope in repo docs  
2. ask AI-powered coding agents to read the docs first  
3. require a plan before implementation  
4. review the plan for scope creep and architecture drift  
5. implement a bounded vertical slice  
6. validate with tests and manual verification  
7. record decisions and lessons learned  

This approach is especially useful in AI-enabled applications, where architecture and trust boundaries matter as much as speed. SaidnDone’s documented implementation approach explicitly uses vertical slices because they surface user value and AI quality issues earlier, and because they make AI-powered coding agents easier to direct in bounded work units.

---

## What I Want My Projects To Show

Through my repos, I want to demonstrate that I can:

- translate ambiguous ideas into scoped product definitions
- make architecture decisions before implementation complexity grows
- use AI coding tools strategically rather than passively
- build iteratively with a clear delivery model
- design AI-enabled workflows with practical human approval boundaries
- create systems that are useful, explainable, and extensible

I’m interested in projects where the real challenge is not “can the model generate something,” but:
- what the workflow should be
- where approval boundaries belong
- how outputs should be structured
- how the system should preserve trust, traceability, and control

---

## Featured Project: SaidnDone

**SaidnDone** is an AI-powered meeting intelligence and follow-through application.

### What it does

It transforms meeting artifacts into:
- structured summaries
- action item candidates
- approved action items
- draft work outputs such as follow-up emails, task breakdowns, and ticket drafts

The product is intentionally built around human review. AI outputs are drafts, not final actions, and the application does not automatically send emails, create project tickets, or modify external systems. That trust-first posture is reflected throughout the README, SPEC, AGENTS, and ARCHITECTURE files.

### Why it matters

Most tools assume a user can already translate messy conversation into structured work.

SaidnDone focuses on that translation layer:
- conversation
- understanding
- extraction
- approval
- bounded draft generation

### Architecture highlights

- Next.js frontend
- FastAPI backend
- PostgreSQL
- Azure Blob Storage
- Redis + Dramatiq workers
- LangChain for AI orchestration
- staged AI pipeline instead of one giant prompt
- approval boundary before downstream draft generation
- traceability from source material to generated outputs

---

## AI Application Design Principles I Care About

A few principles show up repeatedly in my work:

- **Plan before implementation**
- **Build one vertical slice at a time**
- **Prefer bounded workflows over vague automation**
- **Use structured outputs instead of fragile free-form generation**
- **Treat user-provided content as untrusted input**
- **Preserve review-first behavior where trust matters**
- **Keep generated candidates separate from approved records**
- **Preserve history instead of overwriting outputs**

These principles became especially important in SaidnDone, where the documented approach and architecture both emphasize deterministic workflows, approval boundaries, and staged processing. 

---

## Areas I’m Interested In

I’m particularly interested in roles and work involving:
- AI Product
- AI Consultant / Solutions Architect
- Technical Strategy
- AI workflow design
- product-minded engineering
- systems that connect business value to disciplined technical execution

I’m most energized by work that blends:
- product judgment
- technical design
- implementation leadership
- practical AI application building

---

## Framework + Projects

- **AI App Starter Framework for AI-powered coding agents**  
  A reusable framework for building applications with AI-powered coding agents using markdown-defined scope, architecture-first planning, vertical slices, reusable prompt files, and implementation guidance.

- **SaidnDone**  
  AI-powered meeting intelligence and follow-through application built using that framework.

---

## What I’m Building Toward

Instead of trying to build isolated demos, I am building a repeatable way of creating AI-enabled applications that shows:
- how to think strategically about product and system design
- how to use AI coding tools responsibly and effectively
- how to structure software delivery in a way that scales across projects

The goal is to make my projects reflect both **what I built** and **how I think**.

---

## Let’s Connect

If you’re interested in:
- AI product development
- AI application architecture
- technical strategy
- human-in-the-loop workflow systems
- disciplined use of AI coding tools

Feel free to connect!

LinkedIn: [Tyler Vance](https://www.linkedin.com/in/tyler-j-vance/)

Email: <tylervance7@gmail.com>
