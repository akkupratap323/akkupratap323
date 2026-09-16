<div align="center">

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:7C3AED,50:2563EB,100:06B6D4&height=220&section=header&text=Aditya%20Pratap%20Singh&fontSize=44&fontColor=FFFFFF&fontAlignY=36&desc=AI%20Systems%20Engineer%20%E2%80%A2%20Founder%20%E2%80%A2%20Open-Source%20Builder&descAlignY=57&descSize=18" alt="Aditya Pratap Singh — AI Systems Engineer" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=23&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=820&lines=Building+production+AI+agents;Engineering+real-time+voice+systems;Designing+evaluation+%26+safety+infrastructure;Turning+AI+research+into+shipped+products" alt="Typing introduction" />
</a>

<p>
  <a href="https://www.linkedin.com/in/aditya-pratap-singh-524a70283/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:akkupratap323@gmail.com"><img src="https://img.shields.io/badge/Email-Let's_Talk-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://drive.google.com/file/d/1icdG8Bms8uVvxiEvH0_NEgzbGIEH8EqW/view?usp=sharing"><img src="https://img.shields.io/badge/Resume-View-8B5CF6?style=for-the-badge&logo=googledrive&logoColor=white" alt="Resume" /></a>
  <a href="https://github.com/akkupratap323"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

![Profile views](https://komarev.com/ghpvc/?username=akkupratap323&style=flat-square&color=2563EB&label=PROFILE+VIEWS)

</div>

## About Me

> **I build production AI products end-to-end — from architecture and backend systems to integrations, evaluations, deployment, and product iteration.**

- **Co-founder, [Verly AI](https://verlyai.xyz/)** — product architecture, voice and chatbot engines, and MCP integrations.
- **Founder, [Saient](https://saientai.xyz/)** — multi-channel AI sales agents across voice, WhatsApp, email, and web.
- **Previously AI Engineering Intern, Nester Labs** — voice-agent evaluation, AI security, and production conversational systems.
- **IIIT Nagpur, Electronics & Communication Engineering.**
- Open to **Applied AI** and **Forward Deployed Engineering** opportunities.

<div align="center">

| `+17.6` Precision@100 | `8+` specialized agents | Real-time voice AI | Reproducible evaluations |
|:---:|:---:|:---:|:---:|
| Lookalike reranking uplift | Tool-connected orchestration | Streaming STT → LLM → TTS | Byte-exact judge replay |

</div>

## Production Products & Live Demos

| Product | What I worked on | Explore |
|:---|:---|:---:|
| **Verly AI** | Product architecture, voice/chatbot engines, and MCP integrations. | [Visit ↗](https://verlyai.xyz/) |
| **Saient** | Multi-channel AI sales platform with voice agents, built end-to-end. | [Visit ↗](https://saientai.xyz/) |
| **nForge** | Voice-agent testing with simulated callers, adversarial probes, and regression evaluations. | [Live ↗](https://nforge.nesterlabs.com/) |
| **nGuard** | AI-native security and agent red-teaming platform developed at Nester Labs. | [Live ↗](http://nguard.nesterlabs.com/) |
| **Production Voice Agent** | Conversational voice AI implementation at Nester Labs. | [Demo ↗](https://ai.nesterlabs.com/) |
| **Intake & Booking Agent** | Voice agent for customer intake and appointment booking. | [Demo ↗](https://intake-demo.nesterlabs.com/) |
| **ImpactVolunteer** | Additional web product work. | [Visit ↗](https://impactvolunteer.com/) |

## Selected AI Projects

### 🦞 Clawspan — Personal AI Chief of Staff

Built from scratch in Python: a voice-driven assistant for terminal tasks, GitHub, AWS checks, research, Gmail, and Calendar. Uses Pipecat for voice I/O and macOS automation for tool execution.

**Highlights**

- Coordinates **8+ specialized agents** across engineering and productivity workflows.
- Connects to GitHub, Gmail, Slack, PostgreSQL, Calendar, terminal, and AWS tooling.
- Uses a three-tier router to resolve common requests without unnecessary LLM calls.
- Hand-written orchestration without LangChain, CrewAI, or another agent framework.

[![Repository](https://img.shields.io/badge/Repository-Clawspan-181717?style=for-the-badge&logo=github)](https://github.com/akkupratap323/Clawspan)
[![Watch Demo](https://img.shields.io/badge/LinkedIn-Watch_Demo-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/feed/update/urn:li:activity:7450145933335429121/)

---

### 🎯 Lookalike Search — Reasoning Beyond Embeddings

Built a reasoning and reranking layer over openFunnel's public API, improving average Precision@100 by **17.6 percentage points across seven hard benchmark seeds**.

The key insight: embeddings measure textual closeness, not categorical sameness. A company that services a vendor may describe itself using the vendor's language and appear closer than the vendor's real competitors.

```text
Overfetch 250 candidates → filter with code → classify relationship → rerank → replay judge
```

| Benchmark seed | Before | After |
|:---|---:|---:|
| Veeva | 58.5 | **88.5** |
| Nubank | 50.0 | **81.5** |
| Shopify | 74.5 | **94.0** |

The system uses DeepSeek for reranking and the benchmark's own OpenAI judge for evaluation. Code, prompts, runs, and **700 judge rationales** are published with a three-command reproduction path.

[![Repository](https://img.shields.io/badge/Repository-Lookalike_Rerank-181717?style=for-the-badge&logo=github)](https://github.com/akkupratap323/lookalike-rerank)
[![Project Breakdown](https://img.shields.io/badge/LinkedIn-Project_Breakdown-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/feed/update/urn:li:activity:7480513716380246016/)
[![Code, Proofs & Runs](https://img.shields.io/badge/Evidence-Code%2C_Proofs_%26_Runs-059669?style=for-the-badge)](https://lnkd.in/d8wGX2Ni)

---

### 🧠 Manus Decoded — Agent Architecture Analysis

An independent nine-layer analysis of Manus's architecture, drawing on public technical material and hands-on usage. The work explores why the harness matters more than the underlying model.

- **Sub-agents isolate context** instead of playing fictional personas.
- **Wide Research** runs 100+ general-purpose agents in parallel.
- **Memory uses files**, glob, and grep instead of requiring a vector database.
- **KV-cache hit rate** is treated as a first-class cost and latency metric.
- **Failures remain in context**, preserving evidence for the next attempt.

[![Repository](https://img.shields.io/badge/Repository-Manus_Decoded-181717?style=for-the-badge&logo=github)](https://github.com/akkupratap323/manus-decoded)
[![Read Breakdown](https://img.shields.io/badge/LinkedIn-Read_the_Breakdown-0A66C2?style=for-the-badge&logo=linkedin)](https://www.linkedin.com/feed/update/urn:li:activity:7464798973388619776/)

## Agents, Writing & Recognition

| Focus | Work |
|:---|:---|
| **Multi-agent orchestration** | Eight specialized agents connected to GitHub, Gmail, Slack, PostgreSQL, and other tools. [Watch the demo ↗](https://www.linkedin.com/feed/update/urn:li:activity:7429348815134081024/) |
| **Featured in Inc42** | OpenClaw work covered in *The New Garage: OpenClaw And India's DIY AI Agent Boom*. [Feature announcement ↗](https://www.linkedin.com/feed/update/urn:li:activity:7436780050890522624/) |
| **Voice AI engineering** | How we engineered a voice AI stack to feel human. [Read the article ↗](https://medium.com/@aditya_32007/solving-the-empathy-cost-paradox-how-we-engineered-the-voice-ai-stack-to-feel-human-d7ef19c1bc5d) |
| **Competitive programming** | 8th rank in the Unstop Coding Challenge and LeetCode global rank 1861 in Biweekly Contest 153. |

## Technical Stack

<div align="center">

[![Core technologies](https://skillicons.dev/icons?i=python,js,ts,c,cpp,fastapi,django,nodejs,express,react,nextjs,redux,tailwind,html,css,postgres,mongodb,supabase,firebase,aws,git,github&perline=11)](https://skillicons.dev)

</div>

<details open>
<summary><b>Programming, web, and backend</b></summary>
<br />

**Programming Languages**<br />
Python · JavaScript · TypeScript · C · C++

**Backend & APIs**<br />
FastAPI · Django · Node.js · Express.js · REST APIs · WebSockets · SSE · API Integrations

**Frontend & Full-Stack**<br />
React · Next.js · Redux · Tailwind CSS · HTML · CSS · Server-Side Rendering

</details>

<details open>
<summary><b>AI, agents, voice, and evaluation</b></summary>
<br />

**AI & Agentic Systems**<br />
LLM Integration · Multi-Agent Orchestration · RAG Pipelines · MCP · Tool Calling · Prompt Engineering · Context Management · Agent Handoffs · Human-in-the-Loop Workflows

**Voice AI & Real-Time Systems**<br />
Pipecat · Deepgram · Cartesia · DeepSeek · Twilio Media Streams · OpenAI Realtime · Streaming STT/TTS · Silero VAD · SmartTurn · Dynamic Voice Switching

**Evaluation & AI Safety**<br />
LLM-as-Judge · Behavioral Testing · Adversarial Testing · Prompt-Injection Probes · Guardrail Evaluation · Transcript Assertions · Regression Testing · Latency Analysis

</details>

<details open>
<summary><b>Data, cloud, automation, and engineering foundations</b></summary>
<br />

**Databases & Authentication**<br />
PostgreSQL · MongoDB · Supabase · Firebase Authentication

**Cloud & Developer Tools**<br />
AWS · Git · GitHub · Docker · GitHub Actions · CLI Development · Deployment · Production Debugging

**Automation & Integrations**<br />
OpenClaw · PyAutoGUI · AppleScript · GitHub · Gmail · Slack · Calendar Integrations

**Observability & Memory**<br />
OpenTelemetry · Langfuse · Prometheus · Mem0 · Graphiti · Qdrant · Neo4j · OpenSearch

**Core Engineering**<br />
Data Structures & Algorithms · Object-Oriented Programming · DBMS · Computer Networks · System Architecture · High-Level Design

</details>

## GitHub Activity

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=akkupratap323&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true" alt="Aditya's GitHub stats" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=akkupratap323&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" alt="Aditya's top languages" />

<img width="92%" src="https://github-readme-activity-graph.vercel.app/graph?username=akkupratap323&theme=tokyo-night&hide_border=true&area=true" alt="Aditya's contribution graph" />

</div>

## Let's Build

I am interested in ambitious AI products where agents must work reliably with real tools, users, latency constraints, and measurable evaluations.

<div align="center">

**Applied AI · Forward Deployed Engineering · Voice AI · Agent Infrastructure**

<a href="https://www.linkedin.com/in/aditya-pratap-singh-524a70283/"><img src="https://img.shields.io/badge/Start_a_conversation-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin" alt="Connect on LinkedIn" /></a>
<a href="mailto:akkupratap323@gmail.com"><img src="https://img.shields.io/badge/Send_an_email-Email-EA4335?style=for-the-badge&logo=gmail" alt="Send an email" /></a>

<br /><br />

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:06B6D4,50:2563EB,100:7C3AED&height=120&section=footer" alt="Footer" />

</div>
