# Agentic Control Hub — Research

Research corpus behind the **Sinet Agentic Control Hub**: a self-hosted platform for supervised AI knowledge work, run on flat-rate consumer AI subscriptions, maintained by a single operator.

This repository holds the *research phase* output — evidence gathered before the architecture spec was written. It is not the platform itself, and there is no code here.

## What's inside

| Path | Contents |
|---|---|
| `Research/` | 18 full research reports (~1 MB of prose), one per topic |
| `briefs/` | The 18 topic briefs that commissioned those reports, plus the shared context every run consumed |
| `Sinet-Research-Presentation.html` | *AI That Pays Off* — an evidence briefing for IT leadership |
| `kokotajlo-interview-summary.html` | Topic-by-topic summary of the Kokotajlo × Diary of a CEO interview |

Both HTML files are self-contained — open them directly in a browser.

## The reports

| # | Report |
|---|---|
| 01 | [Execution engines & the adapter layer](Research/01-execution-engines-and-adapters.md) |
| 02 | [Provider watchlist & onboarding criteria](Research/02-provider-watchlist-and-onboarding-criteria.md) |
| 03 | [Intake, planning & specification pipeline](Research/03-intake-planning-spec-pipeline.md) |
| 04 | [Verification & quality loops](Research/04-verification-and-quality-loops.md) |
| 05 | [Agent loop & harness engineering](Research/05-agent-loop-and-harness-engineering.md) |
| 06 | [Orchestration & multi-agent architecture](Research/06-orchestration-and-multiagent.md) |
| 07 | [Context engineering: assembly, rot, and per-stage cost structure](Research/07-context-engineering.md) |
| 08 | [Durable state, checkpointing & crash recovery](Research/08-durable-state-checkpointing-recovery.md) |
| 09 | [Consumption metering, quota handling & scheduling](Research/09-metering-quota-scheduling.md) |
| 10 | [Sandboxing & the confinement ladder](Research/10-sandboxing-confinement.md) |
| 11 | [Memory & knowledge architecture](Research/11-memory-and-knowledge-architecture.md) |
| 12 | [Evals, observability & the benchmark practice](Research/12-evals-observability-benchmark.md) |
| 13 | [Deliverables, review & git integration](Research/13-deliverables-review-git.md) |
| 14 | [OSS harvest validation & adoptable-component sweep](Research/14-oss-harvest-validation.md) |
| 15 | [Worker ontology & domain-specific agents](Research/15-worker-ontology-and-domain-agents.md) |
| 16 | [The local-models layer (the permanent free tier)](Research/16-local-models-layer.md) |
| 17 | [Platform stack & process architecture](Research/17-platform-stack-architecture.md) |
| 18 | [Codor harvest addendum: what to copy, what not to copy](Research/18-codor-harvest-addendum.md) |

## Method

Each report was produced by a deep-research harness: multiple fan-out search angles per topic, primary-source fetching, and an adversarial verification pass attacking the report's most load-bearing conclusions (verdicts folded into the text). Claims are tiered PRIMARY / SECONDARY, and access dates are recorded inline.

Reports 01 and 02 are standing context for all engine and provider facts; later reports cite them rather than re-researching the same ground.

## Reading it

Start with [`briefs/00-shared-context.md`](briefs/00-shared-context.md) — it states the project in a paragraph, the fixed constraints D1–D10 the research had to work *within*, and the post-mortem lessons from Nexus (the predecessor) that the rebuild treats as standing policy. Every report assumes it.

## Status

Point-in-time evidence, dated **July 2026**. The AI provider landscape moves fast; treat provider terms, pricing, and product claims here as snapshots with their recorded access dates, not as current fact.
