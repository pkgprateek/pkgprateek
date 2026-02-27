# Prateek Kumar Goel

I build **production-grade AI systems**: the stuff around the model that makes it reliable (data → retrieval → inference → evaluation → ops).

Right now I’m focused on **LLM infrastructure + agent reliability**:
- reducing “looks done but isn’t” outcomes
- enforcing verification and safe tool usage
- keeping latency and cost predictable

## Current work

### Setu — governance for coding agents
An OpenCode plugin that adds **discipline + verification** to agentic coding workflows.

- Repo: https://github.com/pkgprateek/setu-opencode  
- Docs: https://deepwiki.com/pkgprateek/setu-opencode  

What it’s trying to do (in plain language):
- force “context-first” behavior (read before write)
- keep work structured (research → plan → implement)
- make verification non-optional (don’t ship until checks pass)

If you’ve ever watched an agent confidently break a repo, this is my attempt at a practical fix.

## What I like building

- **LLM systems**: retrieval, routing, evaluation loops, guardrails, monitoring
- **Backend and distributed systems**: APIs, queues, reliability, performance
- **Performance work**: latency, throughput, GPU/CPU efficiency, cost control
- **Developer tooling**: workflows that make engineering calmer instead of chaotic

## How I work

I default to a few principles:
- Make failure modes explicit (what can go wrong, how we detect it, how we recover)
- Prefer boring, testable infrastructure around “intelligence”
- Log and trace everything worth debugging
- Keep the feedback loop tight (small diffs, quick verification, repeat)

## If you want to collaborate

- Issues/PRs on Setu are welcome.
- If you’re shipping an AI product and want a second set of eyes on reliability/cost/perf, I’m open to conversations.

**Contact**
- Email: hello@prateekgoel.com  
- LinkedIn: https://linkedin.com/in/prateekkgoel
- X(Twitter): https://x.com/prateekkgoel