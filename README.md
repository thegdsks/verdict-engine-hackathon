# Verdict — Multi-Agent Debate Engine

> AI agents that research, argue, cross-examine, and deliver structured verdicts.

**Coming soon at [askverdict.ai](https://askverdict.ai)**

## What is Verdict?

Verdict transforms decision-making by running structured adversarial analysis. Submit any question and Verdict spawns AI agents with distinct personas who research both sides, argue with evidence, cross-examine each other's claims, and synthesize a structured verdict.

No more rephrasing prompts 15 times hoping for a better answer. Get every perspective in one structured debate.

## What's Coming

- **Web App** — Live debate streaming with real-time agent activity at askverdict.ai
- **SDK** — `@verdict/engine` npm package for programmatic access
- **CLI** — `verdict "Should we use Postgres or MongoDB?" --mode fast`
- **MCP Server** — Use Verdict directly inside Claude Code and Claude Desktop

## How It Works

1. You ask a question
2. Verdict spawns 3-5 AI agents with distinct personas
3. Agents research, present opening arguments, and cross-examine each other
4. Every claim is tracked in an argument graph (standing, challenged, rebutted, conceded)
5. A synthesizer weighs all evidence into a structured verdict with an emergent decision matrix

## Built With

TypeScript · Anthropic Claude (Opus / Sonnet / Haiku) · Next.js · SSE Streaming

## Origin

Built as a solo project for the Anthropic Opus 4.6 Hackathon (Feb 2026). Now evolving into a full product.

## Contact

Follow development at [askverdict.ai](https://askverdict.ai)
