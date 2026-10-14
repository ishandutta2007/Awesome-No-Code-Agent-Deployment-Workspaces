# Awesome-No-Code-Agent-Deployment-Workspaces

## Top No-Code Agent Deployment Workspaces Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Drag-and-Drop Orchestration Canvases, Visual Agent Building & Departmental Bot Deployment*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **No-Code Agent Deployment Workspaces**. These tools give business departments — support, operations, marketing, finance — a drag-and-drop canvas to assemble AI agents from LLM nodes, tool connectors, and knowledge bases, then deploy them as internal bots or customer-facing assistants without engineering tickets.

**Examples** include Dify, Flowise, MindStudio, Lindy, Rivet, Relevance AI, Activepieces, n8n Cloud, Stack AI, and Zapier Central (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom node ecosystems, and transparent agent runtimes — ideal for platform teams prioritizing data sovereignty, developers building internal agent infrastructure, and organizations avoiding per-task cloud pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Dify Cloud](https://dify.ai/)**  
  Managed version of the open-source Dify platform with free Sandbox tier and paid plans. Build agents, agentic workflows, RAG pipelines, and chatbots with a visual editor, then publish as web apps or APIs. Supports hundreds of models and a plugin marketplace .

- **[MindStudio](https://www.mindstudio.ai/)**  
  No-code AI agent builder for non-technical users. AI-guided agent creation, 500+ actions in the open-source MindStudio Connector Registry (MSCR), full VM execution for Custom Functions, and debugger insights AI built into run logs. Supports Claude Sonnet 4.5, GPT-5, Gemini 2.5 Flash Image, and Runway Gen-4 Turbo .

- **[Lindy](https://www.lindy.ai/)**  
  AI executive assistant that runs your work life autonomously. Handles email triage, meeting prep, smart scheduling, and follow-ups. Delegate via iMessage, SMS, Slack, email, or web app. SOC 2 Type II, HIPAA, GDPR, PIPEDA compliant .

- **[Rivet](https://rivet.ironcladapp.com/)**  
  Visual programming environment for AI agent workflows from Ironclad. Node-based graph editor for building and debugging agent logic.

- **[Relevance AI](https://relevanceai.com/)**  
  Collaborative agent platform with **Invent 2.0** that interviews you, analyzes documentation to map processes, then creates end-to-end agentic business processes from coordinated specialist agents. Includes built-in testing, governance, and value tracking .

- **[Stack AI](https://www.stack-ai.com/)**  
  Enterprise no-code platform for building AI assistants and agents with visual flow builder and enterprise-grade security.

- **[Zapier Central](https://zapier.com/central)**  
  AI-powered automation workspace within Zapier for building bots that connect to 6,000+ app integrations.

## Open-Source GitHub Projects

- **[Dify](https://github.com/langgenius/dify)**  
  **The most-starred open-source LLM application development platform** (149,000+ GitHub stars) combining visual workflow builder, agent framework, RAG pipelines, and knowledge-base management in one self-hostable product . Supports five application types: Chatbot, Agent, Text Generator, Chatflow, and Workflow. Deploy via single-command Docker Compose. **Modified Apache 2.0 license** — multi-tenant SaaS use requires commercial license; logo/copyright must remain in frontend . Plugin ecosystem introduced in v1.0 (2025) with marketplace. Best for teams wanting a self-hostable, visual-first alternative to code-based frameworks.

- **[Flowise](https://github.com/FlowiseAI/Flowise)**  
  **Y Combinator-backed open-source drag-and-drop tool for building customized LLM flows** (Apache 2.0 licensed) . Built on top of LangChain, providing a visual interface to connect components like PDF loaders, embeddings, vector databases, and LLMs — "like LEGO" for AI apps . Features chatflow canvas, API/embed deployment, custom tool creation, and multi-agent orchestration . Self-hosted via Docker or npm. Best for developers who want LangChain power with visual assembly speed .

- **[n8n](https://github.com/n8n-io/n8n)**  
  **Fair-code workflow automation platform with ~200,000 GitHub stars and 100M+ Docker pulls** . Combines visual node-based editor with full JavaScript/Python code support, 400+ native integrations, and ~70 AI/LLM nodes . Self-hosted Community Edition is free forever with unlimited workflows and executions . **Sustainable Use License** (fair-code, not OSI-approved) — prohibits reselling n8n as a SaaS . Best for teams needing deep integration breadth plus AI agent capabilities in one platform. Self-hosting recommended for advanced users only .

- **[Activepieces](https://github.com/activepieces/activepieces)**  
  **MIT-licensed, AI-first automation platform with 23,000+ GitHub stars** — Y Combinator backed . 280+ integrations ("pieces") written in TypeScript, with **every piece automatically exposed as an MCP server** — roughly 400 tools that Claude Desktop, Cursor, and Windsurf can call directly . Built-in MCP server is the largest open-source MCP toolkit for AI agents . Self-hosted on Railway gives unlimited tasks at ~$5–15/month flat — no per-task billing . Best for teams wanting fully OSI-approved open-source with AI-native MCP capabilities.

- **[Langflow](https://github.com/langflow-ai/langflow)**  
  **Visual platform for building and deploying AI-powered agents and workflows** with built-in API and MCP servers that turn every workflow into a tool integratable into any framework . Features visual builder, source code access for custom Python components, interactive playground with step-by-step control, multi-agent orchestration with conversation management, and deployment as API or MCP server . Observability integrations with LangSmith and LangFuse . Apache 2.0 licensed. **Langflow Desktop** available for Windows and macOS with all dependencies included .

- **[Sim Studio](https://github.com/simstudioai/sim)**  
  **Open-source platform for building AI agent workflows visually, "like Figma"** — Y Combinator backed with 60,000+ developers . Drag-and-drop canvas for LLMs, tools, and connections to Slack, Gmail, Supabase, Pinecone, and more. Built-in Copilot generates nodes, fixes errors, and improves flows from natural language . Supports hosted and local models, vector databases, and webhook triggers. **SOC2 and HIPAA compliant** . Self-host with Docker Compose or Kubernetes, or run fully local with Ollama . Next.js + PostgreSQL with pgvector + ReactFlow stack .

- **[OpenRigor](https://github.com/wangyunjeff/OpenRigor)**  
  Clean-room open-source persistent AI-agent workspace with durable runs, sandboxed tools, replayable SSE events, and artifact delivery . Chat-first product that can plan work, run tools in an isolated workspace, stream progress, survive disconnects, and return inspectable files . Includes task templates with preview-before-send, model and routing controls (Sol/Terra/Luna with Low to Max reasoning depth), and inspectable execution with expandable tool steps . Local alpha with real Codex app-server execution .

### Additional Strong Open-Source Options

- **GenXAI Framework** — Open-source framework and CLI for building multi-agent workflows with YAML definitions. Supports agent registries, graph-based orchestration (RoundRobinFlow, SelectorFlow, P2PFlow), and tool creation/export. PyPI package with `genxai` CLI for workflow execution .
- **Bannaha** — Open-source multi-agent coordination harness with support for Anthropic, OpenAI, Google ADK, Hermes, and custom agents. Implements voting, blackboard, and single-agent strategies with cost tracking and budget limits. PyPI package with `bannaha list`, `bannaha prices`, and fleet configuration .
- **Open WebUI** — Self-hosted web interface for LLMs with pipeline support for custom agent workflows and RAG capabilities.
- **LibreChat** — Open-source ChatGPT alternative with multi-channel support and plugin architecture for custom agent deployment.

**Frameworks for building custom systems**: Combine **Dify** for full-platform agent building with RAG and knowledge management, **Flowise** for LangChain-powered visual flows, **Activepieces** for MIT-licensed automation with built-in MCP server, **n8n** for deep integration breadth with AI nodes, and **Langflow** for Python-customizable visual agent orchestration to build a complete self-hosted no-code agent deployment stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- No-code agent deployment workspaces must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, HIPAA), and organizational security policies. **Visual workflows can obscure data flows** — teams should review what data each agent node accesses and where it is sent. Self-hosted deployments require proper security hardening, especially for webhook endpoints and API keys.
- License terms vary significantly: Dify uses a modified Apache 2.0 with commercial restrictions, n8n uses fair-code (not OSI-approved), and Activepieces CE is MIT. Review licensing before commercial deployment .

---

**Made for operations teams, platform engineers, AI adoption leads, and developers building internal agent deployment platforms.**  
Let's make no-code agent deployment more open, governable, and department-friendly.
