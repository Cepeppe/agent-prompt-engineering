# AI Agent Prompt Engineering Guide

A structured methodology for crafting high-quality prompts for AI agents and large language models. This guide provides a universal template, runtime commands, and fully worked examples that help you get consistently better results from AI systems across coding, writing, planning, and analysis tasks.

## What's Inside

### Part I — Template Skeleton + Runtime Commands

A copy-paste-ready prompt skeleton with clearly defined sections:

| Section | Purpose |
|---|---|
| **Role** | Sets the agent's expertise, seniority, and cognitive lens |
| **Context** | Situation, domain/constraints, and target audience |
| **Task** | Primary objective (action verb first) + numbered sub-tasks |
| **Constraints** | Must do, must not do, and quality bar |
| **Output Format** | Structure, style, and length specifications |
| **Examples** | Good and bad output samples for calibration |
| **Verification** | Checklist of specific, testable assertions |
| **Runtime Instructions** | 10 agent-facing commands that govern execution behavior |

### Part II — Section Reference

A human-facing explanation of each skeleton section, including strong vs. weak examples and best practices for filling in each field.

### Part III — Full Prompt Examples

Five complete, production-ready prompts across different domains:

1. **REST API Endpoint** — Python/FastAPI POST endpoint with Pydantic v2, async, and error handling
2. **Refactor for Testability** — Decoupling a legacy Python module into layered, testable architecture
3. **Product Blog Post** — B2B SaaS feature announcement (600-800 words, publish-ready)
4. **90-Day Onboarding Plan** — Senior Product Manager onboarding with phased structure and success criteria
5. **Competitive Positioning Analysis** — Gap analysis with positioning statement for a B2B SaaS product

## Runtime Commands

The guide includes 10 runtime commands designed to prevent common AI agent failure modes:

| Command | What It Prevents |
|---|---|
| **Plan First** | Coding without architecture leads to rework |
| **Explain Before You Code** | Wrong design produces wrong implementation |
| **Log Every Assumption** | Silent assumptions become invisible bugs |
| **Run → Capture → Fix → Repeat** | Untested code accumulates errors |
| **Log Dead Ends** | Agents retry the same broken approach indefinitely |
| **Regression Check After Every Fix** | Fix-one-break-two thrashing |
| **Milestone Checkpoint** | No known-good state to roll back to |
| **Self-Review Pass** | Inline writing misses errors that separate review catches |
| **Context Checkpoint** | Long tasks lose state when context is truncated |
| **Update Documentation As You Go** | Docs deferred to the end are always incomplete |

**Minimum set for any coding task:** Plan First, Explain Before You Code, Run→Capture→Fix→Repeat, Regression Check, Self-Review Pass.

**For longer or multi-session tasks, add:** Log Every Assumption, Log Dead Ends, Milestone Checkpoint, Context Checkpoint.

## Files

- [`AI_Agent_Prompt_Engineering_Guide.pdf`](AI_Agent_Prompt_Engineering_Guide.pdf) — The complete guide (12 pages)
- [`prompt_skeleton.txt`](prompt_skeleton.txt) — The template skeleton and runtime commands as plain text, ready to copy into your prompts

## How to Use

1. Copy the skeleton from [`prompt_skeleton.txt`](prompt_skeleton.txt)
2. Fill in every `[bracketed]` field for your specific task
3. Select the runtime commands appropriate for your task type
4. Paste the completed prompt into your AI agent of choice
5. Use the verification checklist to validate the output
