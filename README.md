# Agents (agents)
An index and topic collection covering AI agents, agent frameworks, and agent runtimes that enable autonomous reasoning, tool use, and multi-step task execution. This profile catalogs the platforms and open-source projects that let developers build, orchestrate, and deploy LLM-powered agents, including foundational frameworks like LangChain, LangGraph, CrewAI, AutoGen, and AutoGPT, hosted agent platforms like Lindy, Relevance AI, and Composio, and provider-native agent runtimes from OpenAI, Anthropic, Google, and Microsoft. Distinct from foundation models and from Agent Skills (capability packages), the Agents topic focuses on the orchestration layer where planning, memory, tool calling, and execution come together.

**URL:** [https://apievangelist.com](https://apievangelist.com)

## Tags:

 - AI Agents, Agent Frameworks, Agent Orchestration, Agent Runtimes, LLM Orchestration

## Timestamps

- **Created:** 2026-05-19
- **Modified:** 2026-05-19

## Common Properties

- [Portal](https://apievangelist.com)
- [GitHubOrganization](https://github.com/api-evangelist)
- [JSONSchema - Agent Definition Schema](https://raw.githubusercontent.com/api-evangelist/agents/refs/heads/main/json-schema/agents-agent-definition-schema.json)
- [JSONSchema - Agent Run Schema](https://raw.githubusercontent.com/api-evangelist/agents/refs/heads/main/json-schema/agents-agent-run-schema.json)
- [JSON-LD](https://raw.githubusercontent.com/api-evangelist/agents/refs/heads/main/json-ld/agents-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/agents/refs/heads/main/vocabulary/agents-vocabulary.yaml)

## Features

| Name | Description |
|------|-------------|
| Planning and Reasoning Loops | Agent frameworks like LangGraph, AutoGen, and CrewAI provide structured loops for planning, reflection, and multi-step reasoning over user goals. |
| Tool Calling and Function Use | Agents invoke external functions, APIs, and aggregated tool catalogs through provider-native tool calling, expanding their reach beyond text generation. |
| Memory and State Management | Frameworks like Letta and LangGraph provide persistent memory, conversation state, and long-running execution context for agents. |
| Multi-Agent Orchestration | CrewAI, AutoGen, and LangGraph enable multiple specialized agents to collaborate, delegate sub-tasks, and reach consensus around a shared goal. |
| Provider-Native Agent Runtimes | OpenAI Assistants, Anthropic Claude tool use, Google ADK, Amazon Bedrock Agents, and Microsoft Azure AI Foundry expose first-party agent runtimes. |
| Browser and Web Agents | Agents like AgentQL and browser-driving frameworks let LLMs navigate real web pages, fill forms, and extract structured data. |
| Observability and Evaluation | Portkey, TrueFoundry, and Bifrost provide tracing, evaluation, cost tracking, and gateway routing across agent runs. |
| Open Governance and Interoperability | The Agentic AI Foundation, kagent, and AgentGateway establish open standards for agent-to-agent communication and runtime portability. |

## Use Cases

| Name | Description |
|------|-------------|
| Customer Support Automation | Hosted agent platforms like Lindy, Relevance AI, and Microsoft Power Virtual Agents handle inbound support tickets and resolve common requests. |
| Research and Knowledge Work | LangChain and LlamaIndex agents combine retrieval over enterprise documents with reasoning to answer complex questions and synthesize briefings. |
| Sales and Outbound Workflows | Agents built on Lindy, Relevance AI, and Composio prospect leads, draft outreach, log CRM activity, and orchestrate multi-step sales sequences. |
| Software Engineering Agents | AutoGPT, AutoGen, and CrewAI-based engineering agents read repositories, draft pull requests, run tests, and iterate on code under human review. |
| Voice and Telephony Agents | LiveKit and similar runtimes power real-time voice agents that handle phone calls, meetings, and live conversations using streaming LLMs. |
| Internal Operations and IT Automation | Agentic platforms like Restack, Trigger.dev, and Stackmint orchestrate long-running internal workflows across SaaS, databases, and identity systems. |
| Multi-Agent Team Simulations | CrewAI and AutoGen model role-based teams (researcher, writer, reviewer) collaborating on a single deliverable. |

## Integrations

| Name | Description |
|------|-------------|
| LangChain | The most widely used open-source framework for building LLM applications, including chains, agents, retrieval, memory, and tool calling. |
| LangGraph | A graph-based runtime from LangChain for stateful, multi-actor, long-running agent workflows with checkpointing and human-in-the-loop. |
| CrewAI | Multi-agent framework for orchestrating role-based agent crews that collaborate on complex tasks. |
| AutoGen | Microsoft's open-source framework for building multi-agent conversations with planner, executor, and critic roles. |
| Composio | Agent execution platform exposing 1000+ apps as governed tools for any agent framework or model. |
| Letta | Stateful agent platform (formerly MemGPT) focused on long-term memory and persistent agent identity. |
| OpenAI Assistants | OpenAI's hosted agent runtime with built-in tool use, retrieval, code interpreter, and threads. |
| Amazon Bedrock Agents | AWS's managed agent runtime over foundation models with action groups, knowledge bases, and guardrails. |

## Artifacts

Machine-readable specifications for the Agents topic, organized by format.

### JSON Schema

- [Agent Definition Schema](json-schema/agents-agent-definition-schema.json)
- [Agent Run Schema](json-schema/agents-agent-run-schema.json)

### JSON Structure

- [Agent Definition Structure](json-structure/agents-agent-definition-structure.json)
- [Agent Run Structure](json-structure/agents-agent-run-structure.json)

### JSON-LD

- [Agents Context](json-ld/agents-context.jsonld)

## Vocabulary

- [Agents Vocabulary](vocabulary/agents-vocabulary.yaml) — Unified taxonomy mapping core resources, actions, workflows, and personas across agent frameworks, hosted agent platforms, and provider-native agent runtimes

## Network

This index references the following AI agent, agent framework, and agent runtime repositories:

- [Agentic AI Foundation](https://github.com/api-evangelist/agentic-ai-foundation)
- [AgentGateway](https://github.com/api-evangelist/agentgateway)
- [AgentQL](https://github.com/api-evangelist/agentql)
- [Amazon Bedrock](https://github.com/api-evangelist/amazon-bedrock)
- [Anthropic](https://github.com/api-evangelist/anthropic)
- [AutoGen](https://github.com/api-evangelist/autogen)
- [AutoGPT](https://github.com/api-evangelist/autogpt)
- [Bifrost](https://github.com/api-evangelist/bifrost)
- [Composio](https://github.com/api-evangelist/composio)
- [CrewAI](https://github.com/api-evangelist/crewai)
- [Google ADK](https://github.com/api-evangelist/google-adk)
- [Google Vertex AI](https://github.com/api-evangelist/google-vertex-ai)
- [Haystack](https://github.com/api-evangelist/haystack)
- [Jentic](https://github.com/api-evangelist/jentic)
- [kagent](https://github.com/api-evangelist/kagent)
- [LangChain](https://github.com/api-evangelist/langchain)
- [LangGraph](https://github.com/api-evangelist/langgraph)
- [Letta](https://github.com/api-evangelist/letta)
- [Lindy](https://github.com/api-evangelist/lindy)
- [LiveKit](https://github.com/api-evangelist/livekit)
- [LlamaIndex](https://github.com/api-evangelist/llamaindex)
- [Microsoft Azure AI Foundry](https://github.com/api-evangelist/azure-ai-foundry)
- [Microsoft Power Virtual Agents](https://github.com/api-evangelist/microsoft-power-virtual-agents)
- [OpenAI](https://github.com/api-evangelist/openai)
- [Portkey](https://github.com/api-evangelist/portkey)
- [Relevance AI](https://github.com/api-evangelist/relevance-ai)
- [Restack](https://github.com/api-evangelist/restack)
- [Stackmint](https://github.com/api-evangelist/stackmint)
- [SuperAgent](https://github.com/api-evangelist/superagent)
- [Toolhouse](https://github.com/api-evangelist/toolhouse)
- [Trigger.dev](https://github.com/api-evangelist/trigger-dev)
- [TrueFoundry](https://github.com/api-evangelist/truefoundry)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
