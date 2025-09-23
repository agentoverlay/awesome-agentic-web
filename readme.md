# Awesome Agentic Web [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> **WIP:** This list is under active development. Contributions welcome via PRs and issues.

> A curated list of components for the **Agentic Web** – where AI agents autonomously interact, collaborate, and transact.

## Open Working Groups

- [DIF – Trusted AI Agents WG](https://identity.foundation/working-groups/trusted-agents.html) – Trusted agent stack.
- [IBM AI Alliance](https://thealliance.ai/) : The AI Alliance is building and advancing open source AI agents, data, models, evaluation, safety, applications and advocacy to ensure everyone can benefit.
- [IETF AI Preferences (AIPREF)](https://datatracker.ietf.org/wg/aipref/about/) – Signal content creators’ AI usage prefs.
- [IETF Web Bot Authentication (BoF)](https://datatracker.ietf.org/doc/bofreq-nottingham-web-bot-authentication/) – Cryptographic identity for bots/agents.
- [OpenID Foundation – AI Identity Management CG](https://openid.net/cg/artificial-intelligence-identity-management-community-group/) – Identity/auth for AI agents.
- [Trust over IP – AI & Human Trust WG](https://www.lfdecentralizedtrust.org/projects/trust-over-ip) – Trust frameworks for AI.
- [Linux Foundation Digital Trust](https://www.lfdecentralizedtrust.org/blog/toip-and-dif-announce-three-new-working-groups-for-trust-in-the-age-of-ai?hsLang=en) – New WGs for AI trust.
- [Linux Foundation AGNTCY](https://github.com/agntcy) : The AGNTCY project is the collective of contributors and maintainers building the Internet of Agents (IoA): an open, interoperable, internet for agent-to-agent collaboration. AGNTCY is proudly part of the Linux Foundation.
- [Project NANDA](https://nandaproject.org/) – Internet of Agents research.
- [W3C AI Agent Protocol CG](https://www.w3.org/groups/cg/agentprotocol) – Interop protocols for agents.
- [W3C AI KR CG](https://www.w3.org/groups/cg/aikr) – Knowledge representation for AI.
- [Open Source AI Agent Projects](https://github.com/e2b-dev/awesome-ai-agents?tab=readme-ov-file#open-source-projects) : Open Source AI Agent Projects

## Papers
- **NANDA Index:** *Beyond DNS: Unlocking the Internet of AI Agents via the NANDA Index and Verified AgentFacts* — arXiv: [2507.14263](https://arxiv.org/abs/2507.14263) (2025).
- *A Novel Zero-Trust Identity Framework for Agentic AI* — arXiv: [2505.19301](https://arxiv.org/abs/2505.19301) (2025).
- *A Survey of AI Agent Protocols* — arXiv: [2504.16736](https://arxiv.org/abs/2504.16736) (2025).
- [*Why Do Multi-Agent LLM Systems Fail?*](https://arxiv.org/abs/2503.13657) : A taxonomy designed to understand MAS failures.

## Concepts

### Agentic Identity & Trust
- **Agentic Identity** – DID/VC-backed identity for agents.
- **Proof of Personhood** – Human-behind-agent checks.
- **Agentic Delegation** – Scoped authority transfer (human↔agent, agent↔agent).
- **Agentic Profiles** – DID-anchored metadata and capabilities.
- **Agentic Registries** – Discovery/verification directories (e.g., NANDA Index).

### Agentic Security & Compute
- **Agentic Security** – Threat models, policy, runtime enforcement.
- **Confidential Computing** – Protect data-in-use.
- **Trusted Execution Environments (TEEs)** – Hardware isolation for agent code.
- **Trust Spanning Protocol (TSP)** – Cross-domain trust “bridge”.

### Protocols & Interaction
- **A2A (Agent-to-Agent)** – Peer interop/messaging.
- **A2P (Agent-to-Protocol)** – Agents as first-class actors in Internet protocols.
- **MCP (Model Context Protocol)** – Agents ↔ tools/data interface.
- **NLWeb** – Conversational endpoints for websites.
- **GNAP** – Fine-grained delegated authorization.
- **OAuth 2.0** – Token-based delegated access.
- **DIDs / VCs** – W3C identity & credential primitives.

### Simulation
- **Agent-Based Simulation** – Synthetic envs for policy/safety.
- **Digital Twins** – Mirrored systems for evaluation.
- **Testbeds** – Multi-agent labs for governance/safety.

## Use Cases

### Agentic Commerce

## Protocols
- **A2A Protocol** — Open source agent-to-agent comms: <https://github.com/a2aproject/A2A>
- **Model Context Protocol (MCP)** — Spec + SDKs: <https://modelcontextprotocol.io> · Org: <https://github.com/modelcontextprotocol>
- **NLWeb** — Toolkit for agent-friendly sites: <https://github.com/nlweb-ai/NLWeb>
- **[Human Context Protocol](https://humancontextprotocol.com/)**:
- **[AP2](https://ap2-protocol.org/)**
- **KYAPay** — Agent identity + payments: Whitepaper <https://www.kyapay.ai/> · Repo <https://github.com/skyfire-xyz/kyapay>
- **Awesome Proof of Personhood** — Curated list: <https://github.com/andorsk/awesome-proof-of-personhood>
- *Trust Spanning Protocol: Strengthening Trust in Human–AI Interactions* — ToIP whitepaper (2025) [PDF](https://trustoverip.org/wp-content/uploads/TSP_-Strengthening-Trust-in-Human-and-AI-Interactions.pdf).
- **GNAP (IETF):** Core [RFC 9635](https://datatracker.ietf.org/doc/rfc9635/), RS connections [RFC 9767](https://datatracker.ietf.org/doc/rfc9767/).
- **OAuth 2.0:** [RFC 6749](https://datatracker.ietf.org/doc/html/rfc6749).
  
## Supplementary Awesome Lists
- **Awesome Trust Registries** — Curated list: <https://github.com/andorsk/awesome-trust-registries>
- **Awesome Confidential Computing** — Curated list: <https://github.com/bpradipt/awesome-confidential-computing>
- **Awesome AI Tools** — Curated list: <https://github.com/mahseema/awesome-ai-tools>

## Videos
- **IETF 123 – AIPREF Session (2025-07-21)** — <https://www.youtube.com/watch?v=peXOXYH8vzM>
- **AIPREF Interim (2025-04-08)** — <https://www.youtube.com/watch?v=yc2lON_eVzk>
- **AI Agent Protocols: From Theory to Practice** — <https://www.youtube.com/watch?v=N_etKamePm0>
- **Scaling the Agentic Web** — <https://www.youtube.com/live/SJ8rFKJ8NHw?si=aCu03ZYaUKo6v5Lc&t=2235>

## Frameworks
TODO

## Libraries
TODO

## Taxonomy Commentary
**How to read this map:**

1. **Agentic Identity** (DIDs/VCs, PoP, Profiles, Registries) — *Who is the agent?*  
2. **Agentic Security** (policy, TEEs, Confidential Compute, TSP) — *How do we secure trust & runtime?*  
3. **Protocols** (A2A, A2P, MCP, NLWeb, GNAP/OAuth) — *How do agents talk & act?*  
4. **Simulation** (ABM, twins, testbeds) — *How do we test before deployment?*

## Contribute
Contributions welcome! Please read the [contribution guidelines](contributing.md) before submitting.

\* Archived projects are marked with a star for historical context.
