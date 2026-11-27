# melt-o-graph (Coming Soon)

Turn production telemetry (metrics, events, logs and traces) into a context graph that helps AI coding agents find more failures and fix them faster while using fewer tokens.

## Stop paying your agent to read logs. Give it the graph.
AI coding agents miss production failures when they search through logs, traces and metrics. Fragmented telemetry and missing context lead to excessive token use and overlooked failures, especially at scale. Pair your coding agent with melt-o-graph to discover and fix more failures, more efficiently.

## How it works
### Collect
Point it at the telemetry you already have: metrics, events, logs and traces.
### Transform
It turns your telemetry into a melt-o-graph: a context graph built deterministically, without calling an LLM. No cloud processing. No LLM tokens.
### Hand off
Your coding agent reads the graph as runtime context to find emerging and hidden failures, then plans the fix. You review.

## Search and discovery
### Search
Start from a known issue. Investigate a failure that starts from an alert, an incident or a support ticket, and find the root cause faster and with fewer tokens.
### Discovery
Identify emerging failures. Ask open-ended questions like "identify all failures." Your coding agent explores the context graph, uncovers hidden failure patterns, and surfaces issues it wouldn't otherwise know to look for.

## A failure pattern library
Build your own library of failure patterns, and keep expanding it with new patterns discovered across your agentic applications. A failure understood once should not have to be rediscovered from scratch.

## Next to your observability platform, not instead of it
An observability platform stores your telemetry. melt-o-graph turns your traces into a context graph of your agentic application's runtime. Detectors run over the graph and return candidate failures with example trace ids. Your coding agent reads them and checks each one against your code.

It runs locally, with no account and no API key, and works with any coding agent that supports MCP, such as Claude Code, Codex and Cursor.
