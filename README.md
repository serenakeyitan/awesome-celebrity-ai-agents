# Awesome Celebrity AI Agents

A curated list of tech and AI leaders who have built or launched personal AI agents, digital twins, and AI-powered tools — focused on quality over quantity.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> This list focuses exclusively on verified tech/AI leaders who have publicly announced their AI agents on X (Twitter). Each entry includes who they are, what they built, and why it matters.

## Contents

- [AI Agent Builders](#ai-agent-builders)
- [Digital Twins & AI Clones](#digital-twins--ai-clones)
- [Platforms & Ecosystem](#platforms--ecosystem)
- [Contributing](#contributing)

---

## AI Agent Builders

Tech leaders who have open-sourced or publicly launched personal AI agent systems.

### Garry Tan

**CEO, Y Combinator** | [@garrytan](https://x.com/garrytan) | 1M+ followers

Open-sourced **gstack** — his complete Claude Code setup that turns a single AI model into a virtual engineering team with 13 specialized agent roles (CEO, Eng Manager, Designer, QA Lead, Release Engineer, etc.). Announced on X in March 2026, it hit 10,000 GitHub stars in 48 hours.

- **What he built**: [gstack](https://github.com/garrytan/gstack) — 10+ opinionated slash commands for Claude Code that separate planning, review, QA, and shipping into distinct AI agent personas
- **Scale**: Averaged 10,000 LOC and 100 PRs/week over 50 days using this setup
- **Key innovation**: A 200ms browser skill (`/browse`) using a long-lived headless Chromium daemon, and the separation of "plan review" from "code review" to prevent AI rubber-stamping
- **Why it matters**: Demonstrates that a non-engineer CEO can ship production software at engineering-team velocity using well-structured AI agent prompts

### Andrej Karpathy

**Founder, Eureka Labs | Former Director of AI, Tesla | Co-founder, OpenAI** | [@karpathy](https://x.com/karpathy) | 1M+ followers

Open-sourced **autoresearch** — an autonomous AI research agent that runs ML experiments overnight without human involvement. Announced on X in March 2026, the post received 8.6M views in two days.

- **What he built**: [autoresearch](https://github.com/karpathy/autoresearch) — a 630-line Python script (MIT License) that automates the scientific method: modify code, train for 5 minutes, evaluate, keep or discard, repeat
- **Results**: In one run, the agent completed 700 experiments over two days, found 20 additive improvements, and cut training time by 11%
- **Key innovation**: Designed for single-GPU setups, making autonomous AI research accessible without cluster-scale compute
- **Why it matters**: First widely-adopted open-source tool proving that AI agents can conduct meaningful ML research autonomously — Shopify's CEO reported a 19% model improvement from running it overnight

---

## Digital Twins & AI Clones

Tech leaders who have created AI replicas of themselves for public interaction.

### Reid Hoffman

**Co-founder, LinkedIn | Partner, Greylock** | [@reidhoffman](https://x.com/reidhoffman) | 3M+ followers

Created **Reid AI** — a digital twin trained on 20+ years of his books, podcasts, interviews, speeches, and articles. The avatar delivers keynotes, responds to audience questions at conferences, and posts on his social channels in 9 languages.

- **What he built**: Reid AI — a GPT-4-based conversational AI paired with a lifelike video avatar (HeyGen for visuals, ElevenLabs for voice cloning)
- **Capabilities**: Dynamic facial expressions, natural voice delivery, accurate lip sync across 9 languages
- **Use case**: Stands in at conferences and speaking engagements when Hoffman is unavailable; shares commentary on his social channels
- **Why it matters**: One of the first major tech investors to fully deploy an AI twin as a public-facing representative, normalizing the concept for enterprise leaders

### Sebastian Siemiatkowski

**CEO, Klarna** | [@klarnaseb](https://x.com/klarnaseb) | 100K+ followers

Used an **AI clone of himself** to deliver Klarna's Q1 2025 financial results and launched an AI-powered CEO hotline where customers can speak directly with his AI replica.

- **What he built**: A hyperreal AI avatar for earnings reports, plus a customer feedback hotline featuring his AI voice clone trained on his voice and business insights
- **Announcement**: The AI avatar video opened with: "It's me, or rather my AI avatar, here to share Klarna's Q1 2025 highlights"
- **Results**: Reported 100M active consumers, fourth consecutive profitable quarter, 15% YoY revenue growth — all delivered by AI
- **Why it matters**: First public-company CEO to delegate official financial communications to an AI clone, proving the concept works for investor-grade communications

---

## Platforms & Ecosystem

### Marc Benioff

**CEO, Salesforce** | [@benioff](https://x.com/benioff) | 1.5M+ followers

Drove Salesforce's "hard pivot" to **Agentforce** — the company's AI agent platform. While not a personal AI clone, Benioff is the most vocal tech CEO championing the AI agent paradigm, comparing the vision to "Iron Man's Jarvis."

- **What he built**: Agentforce — an enterprise platform for building and deploying autonomous AI agents on top of Salesforce apps
- **Scale**: 380,000 AI agent conversations in 90 days with 84% resolution rate
- **Vision**: Publicly floated rebranding the entire company as "Agentforce" (though Salesforce later called this "theoretical")
- **Why it matters**: Represents the enterprise institutional bet on AI agents, with the company hiring no new engineers in 2025 due to AI productivity gains

---

## Key Themes

| Trend | Leaders | Signal |
|---|---|---|
| **Open-source AI agent tooling** | Garry Tan, Andrej Karpathy | Tech leaders open-sourcing their personal AI workflows for others to adopt |
| **Executive digital twins** | Reid Hoffman, Sebastian Siemiatkowski | Senior leaders creating AI replicas for communication and public engagement |
| **Enterprise agent platforms** | Marc Benioff | Companies rebuilding their core products around AI agents |

---

## Contributing

Contributions welcome. Please read the [contribution guidelines](CONTRIBUTING.md) first.

**Inclusion criteria:**
- Person must be a recognized leader in tech or AI
- AI agent/twin must be publicly announced (ideally on X/Twitter)
- Must be verifiable with credible sources
- Quality over quantity — we intentionally keep this list small and curated

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, the contributors have waived all copyright and related rights to this work. See [LICENSE](LICENSE) for details.
