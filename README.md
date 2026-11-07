### Stan Huseletov

**VP of AI who still ships code.** I build agent infrastructure, then try to break it before I believe it.

VP, AI Centre of Excellence at **Trilogy** · Founder of **[Expanova](https://expanova.io)** · Sofia, Bulgaria

[huseletov.com](https://www.huseletov.com) · [expanova.io](https://expanova.io) · [LinkedIn](https://www.linkedin.com/in/huseletov/) · [stanislav.huseletov@gmail.com](mailto:stanislav.huseletov@gmail.com)

[![Google me](https://img.shields.io/badge/Google%20me-huseletov-4285F4?style=for-the-badge&logo=google&logoColor=white)](https://www.google.com/search?q=huseletov)

---

**What I do at work** (employer code stays private, so here is the shape of it)

- **AI cost infrastructure.** Co-led an internal gateway that pools subscription capacity across coding agents, routes requests, and falls back to metered APIs only when it has to. It started with coding agents and now carries broader API workloads.
- **Educational ML.** Lead an engineering team training and evaluating models that write and grade school content: supervised fine-tuning, preference tuning, best-of-N selection, and the evaluation harnesses that decide what ships.
- **Agents in production.** Run a fleet of long-lived agents that fine-tune, evaluate and chain the next experiment without a human in the loop. The bus they talk over is open source below.

**Featured**

| | |
|---|---|
| [**agentize**](https://github.com/StanHus/agentize) | `npx agentize` gives any repo a persistent agent: memory, a ranked task ledger, self-verification and a filesystem agent mesh. Works with Claude Code, Codex, Cursor and OpenClaw. |
| [**agent-bus**](https://github.com/StanHus/agent-bus) | The message bus and agent loop behind my multi-agent fabric. Delivery by atomic file rename: no broker, no ports, no dependencies, survives crashes. |
| [**expanova-labs**](https://github.com/StanHus/expanova-labs) | Expanova's research lab: cheap open models plus sound oracles (Lean, Dafny, Bend), with pre-registered studies and failures published alongside wins. |
| [**pnrd2-guard**](https://github.com/StanHus/pnrd2-guard) | The soundness gate from the lab's Dafny study. Separates genuinely solved programs from ones that game the spec. Small enough to read in ten minutes. |
| [**tg-notetaker**](https://github.com/StanHus/tg-notetaker) | Part of **Shadow**, my personal agent: joins Telegram voice chats, transcribes and posts the notes. Written by the agent itself. |

**Writing:** [Spiky points of view](https://www.huseletov.com/spiky-points-of-view) · [How to do agentic development](https://huseletov.com/posts/how-to-do-agentic-development) · [How to OpenClaw](https://huseletov.com/posts/how-to-openclaw) · [How to Shadow](https://trilogyai.substack.com/p/how-to-shadow)

**Also:** [**WWVCD**](https://github.com/StanHus/WWVCD) (*What Would Vin Claudel Do?*): `npx wwvcd "<problem>"` searches a database of agent-architecture patterns for how state-of-the-art coding agents handle the edge case your agent is stuck on.

**Open source elsewhere:** contributor to [OGP, the Open Gateway Protocol](https://github.com/dp-pcs/ogp) for federated agent-to-agent communication.

<sub>Many of these repos were built by coding agents under my direction, and their histories show it. That is how I work.</sub>
