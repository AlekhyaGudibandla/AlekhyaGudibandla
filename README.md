<div align="center">

<h1>
  <img src="./my_avatar.gif" width="200px" alt="Alekhya Gudibandla"/>
  Hey, I'm Alekhya 👋
</h1>

</div>

### Software Engineer · AI Systems · Backend · Full-Stack · Distributed Systems

**I like building things that are deceptively simple to use and surprisingly interesting to engineer underneath.**

I enjoy taking real-world problems, understanding what makes the underlying workflow messy or repetitive, and turning them into software that is **simpler, faster, more intelligent and easier to use**.

Sometimes that's a few lines of code.

Sometimes it's a distributed system.

Sometimes it's an AI agent.

And sometimes it's realizing that the complicated solution wasn't necessary in the first place.

<br/>

<div align="center">
  <a href="https://linkedin.com/in/alekhya-gudibandla-3571b5256">
    <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/AlekhyaGudibandla">
    <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="https://leetcode.com/u/alekhyagudibandla2005/">
    <img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" alt="LeetCode"/>
  </a>
</div>

---

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=18&duration=2800&pause=900&center=true&vCenter=true&width=760&lines=Building+systems%2C+not+just+features.;AI+%2B+software+engineering+%2B+systems.;Making+complex+things+feel+simple.;Always+curious+about+what%27s+under+the+abstraction." alt="Typing animation"/>
</div>

---

## 👩‍💻 A little about me

I'm interested in the **full engineering stack** — from algorithms and data structures to backend systems, databases, distributed architectures, cloud infrastructure and modern AI.

I tend to start with the problem rather than the technology.

If a workflow involves people repeatedly copying information, coordinating between systems, waiting for something that doesn't need to be synchronous, or making the same decision over and over, I start wondering whether software can remove some of that work entirely.

That curiosity has taken me across:

**software engineering → backend → distributed systems → AI → multimodal systems → real-time applications**

I enjoy both sides of engineering:

**the "how do we make this work?" side**

and

**the "how do we make this feel effortless?" side.**

---

# ⚙️ Engineering Stack

### Languages

`Java` · `Python` · `TypeScript` · `JavaScript` · `SQL`

### Algorithms & Problem Solving

`Data Structures` · `Algorithms` · `Complexity Analysis` · `Recursion` · `Backtracking` · `Binary Search` · `Sliding Window` · `Two Pointers` · `Trees` · `Graphs` · `Heaps` · `Tries` · `Union-Find` · `Greedy` · `Dynamic Programming`

### Backend Engineering

`Node.js` · `Express` · `FastAPI` · `REST APIs` · `API Design` · `Authentication` · `Authorization` · `JWT` · `WebSockets` · `Async Programming`

### Databases & Data Systems

`PostgreSQL` · `MySQL` · `MongoDB` · `Redis` · `Vector Databases`

`Data Modeling` · `Transactions` · `Indexes` · `Query Optimization` · `Connection Pooling` · `Caching` · `Cache Invalidation`

### Distributed Systems

`Microservices` · `Event-Driven Architecture` · `Message Queues` · `Background Workers` · `Asynchronous Processing` · `Load Balancing` · `Horizontal Scaling` · `Replication` · `Partitioning` · `Sharding` · `Eventual Consistency` · `Idempotency` · `Retries` · `Fault Tolerance` · `Rate Limiting` · `Distributed Locks`

### AI Engineering

`LLMs` · `Agentic AI` · `Multi-Agent Systems` · `RAG` · `Embeddings` · `Vector Search` · `Hybrid Retrieval` · `Reranking` · `Tool Calling` · `Structured Outputs` · `Prompt Engineering` · `AI Evaluation` · `Guardrails` · `LLM Observability`

`LangChain` · `LangGraph` · `PyTorch`

### Multimodal & Voice AI

`Computer Vision` · `Multimodal Models` · `Speech-to-Text` · `Text-to-Speech` · `Voice Agents` · `Streaming Audio` · `Real-Time AI` · `Human Handoff`

### Cloud & Infrastructure

`Linux` · `Docker` · `AWS` · `EC2` · `S3` · `RDS` · `IAM` · `CI/CD` · `GitHub Actions` · `Monitoring` · `Logging`

---

# 🤖 AI Engineering

AI is one of the areas I find most exciting because the interesting engineering increasingly happens **around the model**, not just inside a prompt.

I'm interested in the progression from:

**Models → Applications → Agents → Workflows → AI Systems**

A production AI system can involve:

```text
User
 │
 ▼
Application
 │
 ├──────── Retrieval ────────► Knowledge
 │
 ├──────── State ────────────► Memory
 │
 ▼
Model
 │
 ├──────── Reasoning
 │
 └──────── Tool Calling
             │
          ┌──┼─────┐
          ▼  ▼     ▼
         DB API  Workflow
          │  │     │
          └──┼─────┘
             ▼
          Execution
             │
             ▼
          Evaluation
```

That means going beyond simply calling an LLM API.

I'm interested in:

- transformer and attention fundamentals
- tokens and context windows
- embeddings and semantic representations
- retrieval architecture
- hybrid search
- reranking
- agent state and memory
- tool calling
- multi-agent orchestration
- structured generation
- model routing and fallbacks
- AI evaluation
- hallucination mitigation
- prompt injection and AI security
- latency and inference cost
- tracing and observability
- human-in-the-loop systems

I like experimenting with new models and frameworks.

But the more interesting question is always:

> **What does this capability actually enable, and where does it belong in the system?**

---

# 🏗️ Systems I enjoy thinking about

<img src="https://media.giphy.com/media/WFZvB7VIXBgiz3oDXE/giphy.gif" align="right" hspace="35" vspace="50" width="200" alt="Coding gif">

I like systems where individual components are simple but their interactions matter.

Things like:

**APIs → services → caches → queues → workers → databases → AI workflows**

and the questions underneath them:

- What should happen synchronously?
- What can happen in the background?
- What belongs in a cache?
- What happens when a dependency fails?
- What happens if an event arrives twice?
- Where does consistency matter?
- What can eventually become consistent?
- How should expensive work be retried?
- How does the system behave as traffic grows?
- Where should state live?
- How do we prevent one slow dependency from taking everything down?

A typical architecture might eventually look something like:

```text
                   Client
                     │
                     ▼
                Load Balancer
                     │
                     ▼
                  API Layer
                ┌─────┼─────┐
                │     │     │
                ▼     ▼     ▼
             Redis   DB    Queue
                       │
                       ▼
                    Background
                      Worker
                       │
                  ┌──────┴──────┐
                  ▼             ▼
               Service       AI Job
                  │             │
                  └──────┬──────┘
                         ▼
                      Persistent
                        State
```

The diagram itself isn't the interesting part.

**Understanding why every box exists is.**

<br clear="right"/>

---

# 🚀 What I've been building

I tend to gravitate toward problems where there is a lot of **manual work hiding behind a deceptively simple user experience**.

These projects explore what happens when those workflows are redesigned around automation, AI and strong software engineering.

---

## 🧾 [Tally AI Native](https://github.com/AlekhyaGudibandla/Tally-AI-Native)

### Re-thinking business accounting around automation

Traditional accounting software is very good at **recording and organizing** what a business does.

But a lot of work happens *before* the record exists:

someone reads an invoice, figures out what it means, enters the transaction, categorizes it, updates inventory, checks payments, reconciles accounts and eventually turns everything into reports.

The question behind this project is:

> **What if the accounting system didn't just record the business — what if it actually understood the business activity happening around it?**

Tally AI Native is designed around that idea.

AI agents can interpret documents and business events, extract structured information, determine the appropriate workflow and execute the deterministic parts through controlled tools.

The interesting engineering challenge is making **probabilistic AI work safely inside a system where financial correctness cannot be probabilistic.**

That means combining AI with deterministic validation, accounting logic, transactions, permissions, auditability and reliable workflows.

**Engineering:**  
`Multi-Agent Systems` · `LLMs` · `Document Intelligence` · `Tool Calling` · `Workflow Orchestration` · `Event-Driven Processing` · `Queues` · `Background Workers` · `PostgreSQL` · `Redis` · `Audit Trails`

---

## ☎️ [AI Receptionist](https://github.com/AlekhyaGudibandla/AI-receptionist)

### Turning a conversation into an executable workflow

Calling a business sounds simple:

> *"Are you open?"*  
> *"Do you have an appointment tomorrow?"*  
> *"Book me for 4 PM."*

But underneath that conversation are business information, calendars, availability, appointment rules, conflict detection and sometimes human escalation.

So instead of building another chatbot, this project explores:

> **What if the conversation itself became the interface to the business?**

The AI Receptionist understands the caller, maintains conversational context, invokes the appropriate tools, checks real availability, books appointments and handles conflicts rather than simply generating a response.

The interesting engineering challenge is **real-time orchestration**.

Speech has to feel natural while the system may simultaneously need to understand the caller, reason about the request, retrieve information and interact with external systems.

**Engineering:**  
`Speech-to-Text` · `Text-to-Speech` · `Voice Agents` · `Streaming` · `Tool Calling` · `WebSockets` · `Scheduling` · `Calendar Systems` · `Conflict Detection` · `Human Handoff`

Designed initially around healthcare while keeping the underlying architecture adaptable to other appointment-driven businesses.

---

## 👗 [AI Wardrobe Manager](https://github.com/AlekhyaGudibandla/AI-wardrobe-manager)

### Making personal recommendations actually personal


The obvious version of a wardrobe app is:

> *"Upload your clothes and get outfit recommendations."*

But clothing recommendations become much more interesting once the system remembers **the person**.

What have they worn recently?

What do they usually like?

What's appropriate for the occasion?

What colours do they prefer?

What combinations have already been used?

How long should something stay out of rotation?

What should be recommended today rather than simply what *can* be recommended?

The system therefore combines visual understanding with personalization and usage history.

The goal isn't to generate more outfits.

> **It's to make the right outfit easier to find.**

**Engineering:**  
`Multimodal AI` · `Computer Vision` · `Embeddings` · `Recommendation Systems` · `Semantic Search` · `Preference Modeling` · `Usage History` · `Personalization`

<br clear="right"/>

---

## 🎯 [Focus AI](https://github.com/AlekhyaGudibandla/Focus-AI)

### Making productivity behave more like a system

Most productivity applications give you another checklist, timer or dashboard.

But sometimes the problem isn't knowing **what** to do.

It's actually doing it.

Focus AI explores a different approach:

> **What if learning and focus were structured as an interactive progression system rather than an endless stream of content?**

Courses become journeys.

Tasks unlock progression.

Focus sessions become meaningful state changes.

Performance can influence what happens next.

Accountability becomes part of the system instead of something the user has to maintain manually.

This turns a simple productivity application into a combination of:

`AI Personalization` · `Recommendation Systems` · `Behavioral Signals` · `Stateful Workflows` · `Progression Logic` · `Real-Time Sessions`

The goal is not another productivity dashboard.

**It's to make doing the work harder to avoid.**

---

# 🧩 Engineering principles

### Fundamentals over fashion.

Frameworks change.

The fundamentals underneath them don't.

---

### Automate the boring parts.

If software can reliably remove repetitive work, it probably should.

---

### Don't use AI just because you can.

Sometimes an LLM is the right tool.

Sometimes a database constraint is better.

Sometimes a queue is the answer.

Sometimes the best architecture is surprisingly boring.

Knowing the difference matters.

---

### Complexity should earn its place.

Distributed systems are fascinating.

They also shouldn't be introduced because a diagram looks impressive.

Every piece of infrastructure should solve a real problem.

---

### Hide complexity from the user.

I love complicated systems.

I don't want the person using them to know they're complicated.

---

### Measure, then optimize.

Latency.

Throughput.

Reliability.

Cost.

Model quality.

If it matters, measure it.

---

# 🌱 Always exploring


Technology moves too quickly to stop being curious.

I'm constantly keeping up with developments across:

`AI Models` · `Agent Architectures` · `Multimodal AI` · `Inference` · `Retrieval` · `Developer Tools` · `Databases` · `Distributed Systems` · `Cloud Infrastructure` · `Real-Time Applications`

Not every new technology needs to become a project.

Sometimes I just want to know:

**What changed?**

**Why does it matter?**

**What problem does it actually solve?**

**And where would I use it?**

That's part of the job.

And honestly, part of the fun.

<br clear="right"/>

---

# 🎨 Outside the architecture diagrams...


I care about the other side of software too.

Good interfaces.

Tiny UX details.

Information hierarchy.

Products that don't make users think unnecessarily.

And occasionally spending far too long deciding whether a button is *actually* in the right place.

Because the end goal isn't:

> **"Look how much technology we used."**

It's:

> **"Look how little the user had to worry about."**

<br clear="right"/>

---

# 📊 GitHub

<div align="left">

<img src="https://github-readme-stats.vercel.app/api?username=AlekhyaGudibandla&show_icons=true&hide_border=true&rank_icon=github" height="170"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AlekhyaGudibandla&layout=compact&hide_border=true" height="170"/>

</div>

---

<div align="left">

### Build things. Understand them. Break them. Make them better.

**Always curious about what happens underneath the abstraction.**

<br/>

</div>
