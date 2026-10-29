# Jon W.

Principal Sales Engineer. 25 years in security — Air Force crypto gear, global
network architecture, enterprise deals at Cisco, SaaS email security. I sell
security for a living. I build these systems so that when I'm across the table
from a CISO talking about agentic AI risk, I'm speaking from the operator's
chair, not the slide deck.

## What's here

Most of this is one system wearing different hats: a personal agentic platform
that has run my home infrastructure 24/7 for the past year — AI agents doing
real operational work under real governance. The questions enterprises are
starting to ask about agentic AI — *what can an agent touch? who approved
that? what did it cost? what does it remember?* — are questions this platform
answers in running code.

- **[atlas-framework](https://github.com/ecpunk/atlas-framework)** — the
  coordination layer. One schema-validated record of what exists, what work is
  in flight, and what each actor — human or agent — is permitted to do. Rules
  as data, propose-confirm writes, drift detection between declared state and
  reality, and one bootstrap script that stands up your own instance.
- **[operator-kernel](https://github.com/ecpunk/operator-kernel)** — the
  constrained alternative to "give the agent a shell." Observes before it
  plans, plans only from pre-authored runbooks, executes only against an
  explicit approval token, and leaves a proof artifact for every run. Kept as
  a reference implementation; the platform now enforces the same contract
  natively.
- **[rubric-judge](https://github.com/ecpunk/rubric-judge)** — a two-stage
  watch pipeline: deterministic gates in code, an LLM judge scoring what
  survives against a prose policy rubric, an append-only audit trail, and a
  feedback loop that turns one-sentence operator corrections into permanent
  behavior.
- **[Mimecast-API-Action-Pack](https://github.com/ecpunk/Mimecast-API-Action-Pack)**
  and **[MimecastAPI2.0](https://github.com/ecpunk/MimecastAPI2.0)** — field
  tooling. What pre-sales engineering looks like when you automate it: 257
  endpoints, starter scripts, and a prompt pack that lets an AI assistant
  scaffold a working integration workspace from one paste.
- **[remote-mcp-server](https://github.com/ecpunk/remote-mcp-server)** —
  lessons learned standing up remote MCP servers: connector handshakes and
  CORS, session memory, keeping keys server-side.
- Hardware — **[CNC-Air-Blaster](https://github.com/ecpunk/CNC-Air-Blaster)**,
  **[Oven-Temp-Monitor](https://github.com/ecpunk/Oven-Temp-Monitor)** — same
  instinct, different substrate. If I depend on it, I want to understand it
  down to the metal.

## Writing

Provisional patent on PII-free authorization — [authorization is momentary;
identity retention doesn't have to be permanent](https://momentarytech.com/2026/02/authorization-is-momentary/).
Published on [insider risk](https://momentarytech.com/2025/09/insider-risk/)
(human nature, not malice, drives most threats) and on [what AI-era fraud
actually looks like](https://momentarytech.com/2026/02/fraud-2026/).
