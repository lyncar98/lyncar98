# Lyndon Carlson

**Applied AI engineer.** I build the evaluation, governance, and release infrastructure that makes LLM agents safe to ship in high-stakes domains — education, finance, insurance, and the public sector.

Director of AI at Trissential. Founding CTO of ChatLPO. I work on the unglamorous layer most teams skip: the harness around the model, not the model itself.

---

### What I work on

- **Evaluation as a release contract** — grader registries (code / model / human), `pass@1` vs `pass@k` vs `pass^k`, calibrated LLM judges, and eval gates that produce a real pass/fail instead of a dashboard number.
- **AI governance that you can query** — an org → project → agent standards cascade, immutable release bundles, Release Decision Records, and a single control library mapped to NIST, ISO/IEC 42001, and the EU AI Act.
- **Production agent reliability** — runtime monitoring, drift and hallucination tracking, online eval sampling, and SLOs that open their own incidents.
- **Forward-deployed patterns** — turning bespoke enterprise AI work into reusable, inspectable templates: MCP-style workflow contracts, retrieval grounding, structured outputs, and human-in-the-loop checkpoints.

---

### Featured writing

- **[Everyone Is Building AI Agents. Almost Nobody Is Evaluating Them Correctly.](https://medium.com/@lyndoncarlson)** — what production-grade eval, governance, release, and observability infrastructure actually looks like.
- **[The Regulation Showed Up in My Architecture Diagram Before It Showed Up in the Law](https://medium.com/@lyndoncarlson)** — how compliance stops being a document and becomes a control plane.
- **[The Forward Deployed Engineer, Explained](https://medium.com/@lyndoncarlson)** — a field guide to the role frontier labs are all hiring for, and what it signals about enterprise AI.

---

### What I'm building here

Open patterns extracted from production work — sanitized, generalized, and runnable.

- **[agent-eval-harness](#)** — a grader registry with `pass^k` consistency scoring and an org→project→agent standards cascade. The code behind the eval article.
- **[mcp-workflow-patterns](#)** — reusable agentic workflow templates: tool contracts, context inputs, eval hooks, fallback behavior.
- **[ai-governance-controls](#)** — one control library, mapped to multiple frameworks.

> Links go live as repos ship. Watch this space, or follow along on [Medium](https://medium.com/@lyndoncarlson).

---

### Find me

[Medium](https://medium.com/@lyndoncarlson) · [LinkedIn](https://www.linkedin.com/in/lyndoncarlson) · [Trissential](https://www.trissential.com)

*I write about applied AI architecture, evaluation, and governance. If your architecture diagram and your regulatory obligations are converging — or colliding — I'd like to hear about it.*
