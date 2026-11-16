# Mohan Raj Dhanapal

**AI Engineer & Architect: LLM agents, RAG, evaluation, and the guardrails that make them safe to run in production.**

I've spent 21 years in software delivery, platforms and operations. These days I build with coding agents every day, and I care most about the unglamorous parts that decide whether an AI system can be trusted: evaluation gates, human approval, tracing, and tests that ship with every change.

Most recently (2024–2026) I built a RAG system on AWS Bedrock and LangChain, a support agent that writes the fix and raises a pull request for a developer to review, and LangGraph multi-agent workflows traced and evaluated in Langfuse. That employer code is private. Everything below is my own work, published under Apache-2.0.

## Featured

| Repo | What it shows |
|---|---|
| [approval-gated-mcp](https://github.com/mohanraj005-dot/approval-gated-mcp) | An MCP server where an agent can draft outbound messages but only send after a human approves the exact draft by fingerprint. Kill switch, rate limit, audit log. |
| [rag-eval-harness](https://github.com/mohanraj005-dot/rag-eval-harness) | Retrieval-augmented QA with citations, a golden-set evaluation (hit@k, MRR, citation and fact coverage) and a CI regression gate. Runs offline, no API key needed. |
| [clauderig](https://github.com/mohanraj005-dot/clauderig) | Five Claude Code plugins I use daily: a model-aware prompt writer and critic, a context-waste auditor, naming with live domain checks, a to-scale floor-plan sketcher, and an adversarial review pair. |
| [atlas-dashboard](https://github.com/mohanraj005-dot/atlas-dashboard) | A cross-project status dashboard on Cloudflare Workers and D1, fed by a local collector. |

## How I build AI systems

- **Agents draft, people approve.** Anything that leaves the system (an email, a merge, a deploy) passes a human gate tied to the exact content.
- **Evaluation before release.** A golden set and a regression gate decide whether a prompt, model or retriever change ships.
- **Tests ship with the build.** Unit and end-to-end tests are written alongside the feature, not after it.
- **Trace everything.** Every query and tool call leaves a record you can replay when something goes wrong.

## Stack

Python · LangGraph · LangChain · RAG and vector search · AWS Bedrock · Anthropic and OpenAI models · Claude Code, MCP, skills and hooks · Langfuse · AWS and Azure · Kubernetes · Docker · Airflow · Snowflake · GitHub Actions

## Contact

[LinkedIn](https://www.linkedin.com/in/mohan-technical-leadership) · open to remote AI engineering work
