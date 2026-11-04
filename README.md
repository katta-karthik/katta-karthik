# Hi there, I'm Katta Karthik! 👋

<p align="left">
  <img src="https://komarev.com/ghpvc/?username=katta-karthik&label=Profile%20Views&color=0e75b6&style=flat" alt="Profile Views" />
  <a href="https://katta-karthik.github.io/"><img src="https://img.shields.io/badge/Portfolio-🌐%20katta--karthik.github.io-38bdf8?style=flat" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/katta-karthik/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:kattakarthik8008@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://takeuforward.org/profile/karthik0712"><img src="https://img.shields.io/badge/DSA%20Portfolio-FF9900?style=flat&logo=codeforces&logoColor=white" alt="TakeUForward" /></a>
</p>

### 🤖 AI Engineer & Autonomous Agent Architect
> **Integrated M.Tech in Computer Science & Engineering** @ **Vellore Institute of Technology** *(Graduated · 2021 – 2026)*  
> Engineering **production-grade multi-agent architectures**, **enterprise RAG lifecycles**, and **self-healing LLM workflows**.  
> Active open-source contributor to core AI agent ecosystems including **LangChain**, **OpenHands**, and **CopilotKit**.

---

## 🚀 About Me

- 🧠 Specializing in **Autonomous Multi-Agent Systems**, **LangGraph Orchestration**, and **Self-Healing LLM Workflows**.
- 🔍 Passionate about **Production RAG**: Hybrid Dense-Sparse Retrieval (BM25 + ChromaDB with RRF) and Cross-Encoder Re-ranking.
- ⚡ Experienced with high-throughput inference engines like **Groq LPU** and open-source models (**LLaMA 3.x, Gemini Flash**).
- 🛡️ Dedicated to **AI Safety, Model Alignment**, and sandboxed tool calling via **Model Context Protocol (MCP)**.
- 🌐 Active **Open Source Contributor** enhancing upstream agent SDKs, tool invocation resilience, and state persistence.
- ♟️ Outside of tech: Competitive chess player and cinema enthusiast.

---

## 🌐 Open Source Contributions

Active contributor to core AI agent frameworks, orchestration engines, and developer SDKs:

| Project | PR | Status | Description |
| :--- | :--- | :--- | :--- |
| **[langchain-ai/design-agent](https://github.com/langchain-ai/design-agent)** | [#50](https://github.com/langchain-ai/design-agent/pull/50) | `🟣 Merged` | **Google Gemini Image Generation Provider**: Added Google image models (`generateContent`) with aspect-ratio mapping, 2K resolution, and parallel generation (+456, -70). |
| **[langchain-ai/design-agent](https://github.com/langchain-ai/design-agent)** | [#38](https://github.com/langchain-ai/design-agent/pull/38) | `🟣 Merged` | **Windows Compatibility Fix**: Added `tzdata` (PEP 615) runtime timezone dependency for Windows and guarded POSIX stat check in test suite. |
| **[langchain-ai/design-agent](https://github.com/langchain-ai/design-agent)** | [#53](https://github.com/langchain-ai/design-agent/pull/53) | `🟢 In Review` | **HostMediaErrorBoundary**: Added error boundary middleware wrapping host media and fetch tools to catch network/API timeouts and return clean error states without crashing agent graphs (+503, -3). |
| **[CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit)** *(18k+ ⭐)* | [#8042](https://github.com/CopilotKit/CopilotKit/pull/8042) | `🟢 In Review` | **Aborted Run Tool Call Handler**: Fixed core agent lifecycle bug where aborted runs left unanswered tool calls causing downstream provider 400 errors (+747, -16). |
| **[OpenHands/software-agent-sdk](https://github.com/OpenHands/software-agent-sdk)** *(45k+ ⭐)* | [#6292](https://github.com/OpenHands/software-agent-sdk/pull/6292) | `🟢 In Review` | **Tool Invocation Parameter Filtering**: Fixed Pydantic `extra_forbidden` crashes when models emit argument variants (e.g. `description` instead of `summary`) (+504, -14). |
| **[TerseAI/durable-actors](https://github.com/TerseAI/durable-actors)** | [#400](https://github.com/TerseAI/durable-actors/pull/400) | `🟢 In Review` | **LangGraph Checkpointer & LangChain Memory**: Built `DurableActorSaver` checkpointer and `DurableActorChatMessageHistory` with WebSocket streaming (+4,532, -7). |
| **[Arvo-AI/aurora](https://github.com/Arvo-AI/aurora)** | [#758](https://github.com/Arvo-AI/aurora/pull/758) | `🟢 In Review` | **Incident Status Sync**: Fixed remediation suggestion status desynchronization by deriving status directly from command execution results (#566). |

### 🔍 Contribution Highlights

#### 1. 🦜 [langchain-ai/design-agent](https://github.com/langchain-ai/design-agent) — Official LangChain Generative Agent Framework
* [![Merged PR](https://img.shields.io/badge/PR%20%2350-Merged-8957e5?style=flat&logo=git&logoColor=white)](https://github.com/langchain-ai/design-agent/pull/50) **Google Gemini Image Generation**: Implemented Google Gemini as a first-class image generation provider via `generateContent`, including 2K resolution requests, aspect-ratio mapping, parallel turn batches, and clean error handling (+456, -70).
* [![Merged PR](https://img.shields.io/badge/PR%20%2338-Merged-8957e5?style=flat&logo=git&logoColor=white)](https://github.com/langchain-ai/design-agent/pull/38) **Cross-Platform Windows Support**: Resolved PEP 615 `ZoneInfoNotFoundError` on Windows by adding `tzdata` and adapting POSIX file permissions in the test suite.
* [![Open PR](https://img.shields.io/badge/PR%20%2353-In%20Review-238636?style=flat&logo=git&logoColor=white)](https://github.com/langchain-ai/design-agent/pull/53) **Host Media Error Boundary**: Built `HostMediaErrorBoundary` middleware to safely intercept external media API timeouts and connection failures, converting unhandled exceptions into actionable `ToolMessage` errors (+503, -3).

#### 2. 🦾 [CopilotKit/CopilotKit](https://github.com/CopilotKit/CopilotKit) (18k+ ⭐) — Open-Source AI Copilot Engine
* [![Open PR](https://img.shields.io/badge/PR%20%238042-In%20Review-238636?style=flat&logo=git&logoColor=white)](https://github.com/CopilotKit/CopilotKit/pull/8042) **Core Run Cancellation & Tool Resolution**: Fixed a critical edge case in `RunHandler.processAgentResult` where cancelled/aborted runs omitted responses for open tool calls, preventing subsequent OpenAI 400 errors. Added full multi-turn regression test coverage (+747, -16).

#### 3. 🤖 [OpenHands/software-agent-sdk](https://github.com/OpenHands/software-agent-sdk) (45k+ ⭐ ecosystem) — Software Agent SDK
* [![Open PR](https://img.shields.io/badge/PR%20%236292-In%20Review-238636?style=flat&logo=git&logoColor=white)](https://github.com/OpenHands/software-agent-sdk/pull/6292) **Resilient Tool Invocation Filtering**: Added boundary-level parameter extraction and alias mapping (`description` / `instruction` -> `summary`) to protect agent execution loops against Pydantic `extra_forbidden` errors while preserving strict validation contracts (+504, -14).

#### 4. ⚡ [TerseAI/durable-actors](https://github.com/TerseAI/durable-actors) — Stateful Agent Persistence
* [![Open PR](https://img.shields.io/badge/PR%20%23400-In%20Review-238636?style=flat&logo=git&logoColor=white)](https://github.com/TerseAI/durable-actors/pull/400) **LangGraph Checkpointer & LangChain Memory Adapters**: Implemented sync/async `DurableActorSaver` checkpointer and `DurableActorChatMessageHistory` with WebSocket streaming and an end-to-end multi-agent time-travel example (+4,532, -7).

---

## 🏆 Featured Flagship Projects

### 1. 🔬 [DeepScope — Autonomous Multi-Agent Deep Research System](https://github.com/katta-karthik/DeepScope)
> An autonomous research platform powered by **LangChain Deep Agents** (`deepagents`) and **LangGraph**. It decomposes complex questions, orchestrates specialized subagents (*Lead Coordinator, Topic Researcher, Fact Verifier*), and uses an external disk-backed workspace to eliminate context window fatigue ("brain fog") and hallucinations.
* **Tech Stack:** Python · LangChain Deep Agents · LangGraph · Subagent Delegation · Filesystem Context

---

### 2. ⚡ [NexusRAG — Complete RAG Lifecycle Platform](https://github.com/katta-karthik/Nexus_RAG)
[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-nexus--doc--rag.streamlit.app-FF4B4B?style=flat&logo=streamlit)](https://nexus-doc-rag.streamlit.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/katta-karthik/Nexus_RAG)

> An enterprise-grade, end-to-end RAG platform demonstrating the full retrieval-augmented generation lifecycle — from a live **7-stage visual ingestion pipeline** to **Dense + Sparse Hybrid Retrieval** (BM25 + ChromaDB with Reciprocal Rank Fusion) and **FlashRank Cross-Encoder reranking** for sub-second, hallucination-free answers with exact citations.
* **Tech Stack:** Python · LangChain · ChromaDB · BM25 · FlashRank · Groq LPU · Streamlit

---

### 3. 🛒 [E-commerce AI Analytics — Autonomous Agentic Data Analyst](https://github.com/katta-karthik/ai_agent_for_ecommerce-data)
[![Live Demo](https://img.shields.io/badge/🌐%20Live%20Demo-ecommerce--data--agent.streamlit.app-FF4B4B?style=flat&logo=streamlit)](https://ecommerce-data-agent.streamlit.app/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=flat&logo=github)](https://github.com/katta-karthik/ai_agent_for_ecommerce-data)

> Transforms natural language business inquiries into validated SQL with a **self-healing retry loop** that catches execution errors, diagnoses schema issues, and rewrites queries automatically. Protected with **Meta Prompt Guard 86M** and exposed over **Model Context Protocol (MCP)**.
* **Tech Stack:** Python · LangGraph StateGraph · Google Gemini · Groq LPU · Meta Prompt Guard · Streamlit · MCP · SQLite

---

## 🛠️ Technical Skills

| Domain | Technologies & Frameworks |
| :--- | :--- |
| **Agentic AI & Orchestration** | `LangGraph (StateGraph)` `LangChain` `Deep Agents` `Multi-Agent Systems` `Model Context Protocol (MCP)` `Self-Healing Loops` `Structured Outputs (Pydantic)` |
| **Advanced RAG & Retrieval** | `Dense + Sparse Hybrid Search` `BM25` `Reciprocal Rank Fusion (RRF)` `FlashRank Reranking` `ChromaDB` `Vector Embeddings` `Semantic Chunking` |
| **LLMs & Inference** | `Meta LLaMA 3.x` `Google Gemini` `Groq LPU` `Prompt Engineering` `Meta Prompt Guard 86M` `AI Alignment & Red-Teaming` |
| **Machine Learning & NLP** | `PyTorch` `Hugging Face Transformers` `Scikit-Learn` `Human-in-the-Loop (HITL) Evaluation` `Fine-Tuning Concepts (PEFT/LoRA)` |
| **Backend & Tools** | `Python` `FastAPI` `Streamlit` `SQL (SQLite/PostgreSQL)` `Docker` `Git` `GitHub Actions` `REST APIs` |
| **Core CS Fundamentals** | `Data Structures & Algorithms` `Object-Oriented Programming (OOP)` `Database Management (DBMS)` |

---

## 📊 GitHub Analytics

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=katta-karthik&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Karthik's GitHub Stats" width="48%" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=katta-karthik&theme=tokyonight&hide_border=true" alt="Karthik's GitHub Streak" width="48%" />
</p>

---

## 📫 Let's Connect!

<p align="left">
  <a href="https://katta-karthik.github.io/"><img src="https://img.shields.io/badge/Portfolio-38bdf8?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/katta-karthik/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:kattakarthik8008@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://github.com/katta-karthik"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://takeuforward.org/profile/karthik0712"><img src="https://img.shields.io/badge/TakeUForward-FF9900?style=for-the-badge&logo=codeforces&logoColor=white" alt="Portfolio" /></a>
</p>

---

<p align="center">
  <em>“Keep learning, keep building!” 🚀</em>
</p>
