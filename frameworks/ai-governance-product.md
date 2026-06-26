# AI Governance as a Product Problem

Most enterprise AI governance fails because it's designed by risk teams, for risk teams. The result is a compliance process that product and engineering experience as a roadblock — something to navigate around rather than build with.

This doc captures how I think about AI governance differently: as a product feature that enables scale, not a gate that limits it.

---

## The wrong mental model

The common mental model: governance is a checklist you complete at the end to get approval to ship.

This fails because:
- Risk issues discovered late are expensive to fix
- Teams learn to game checklists rather than internalize the intent
- Each use case gets reviewed as if it's the first one, with no learning across the portfolio

---

## The right mental model

Governance is infrastructure. Like security or observability, it's most valuable when it's built into the product and delivery process — not bolted on at the end.

When I say "100% of platform traffic covered by guardrails and LLM observability," that's not a compliance stat. It's a product capability: the platform can be trusted at scale because the controls are structural, not procedural.

---

## What this looks like in practice

**Guardrails as product features**

Safety controls, content filters, and PII protection are specified in product requirements — not added post-launch. They have acceptance criteria and are tested in QA the same way any other feature is. If a guardrail fails in staging, the use case doesn't ship.

**LLM observability as a data product**

Every prompt and response on the platform is logged, tagged, and queryable. This serves two purposes: risk teams can audit what the system is doing, and product teams can use the data to improve prompts, identify failure modes, and prioritize fixes. The same infrastructure serves compliance and product development.

**MRM review as a delivery milestone**

In financial services, model risk management (MRM) review is required for certain AI use cases. Rather than treating this as an unpredictable external dependency, I map the MRM path at intake, build the required documentation into the delivery process, and schedule review as a sprint milestone. When MRM review is predictable, it's fast. When it's ad hoc, it's slow.

**Risk classification at the start, not the end**

Every use case is classified by risk tier at intake (based on data sensitivity, regulatory exposure, and potential for harm). That classification drives the governance path — not all use cases need the same level of review. Low-risk use cases shouldn't have to wait for the same process as high-risk ones.

---

## The benefit of doing this well

When governance is built into the product:

- **Teams move faster**, not slower — they know what's expected before they start
- **Risk stakeholders trust the platform** — they're not reviewing one-offs, they're auditing a system they've already approved
- **Scale becomes possible** — you can go from 9 use cases to 43 without proportional growth in governance overhead
- **The platform becomes a credible enterprise asset** — executives and regulators can point to it as evidence that AI is being managed responsibly

---

## What I've learned from getting it wrong

Early in my time at Ally, a use case went through three rounds of MRM review because the initial documentation didn't address the right questions. That cost four weeks. The fix wasn't a better checklist — it was getting an MRM stakeholder into the intake conversation early enough to shape the documentation requirements before the use case was built.

The lesson: governance as a product problem means bringing the right stakeholders into discovery, not just into review.
