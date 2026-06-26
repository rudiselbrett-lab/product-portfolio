# Scaling Ally.ai — Enterprise GenAI Platform

**Company:** Ally Financial  
**Role:** AI Product Manager  
**Team:** Two agile delivery teams + cross-functional partners across ERM, MRM, data science, and 10 business lines  
**Timeline:** November 2024–Present

---

## Context

Ally.ai is an internal GenAI platform deployed across Ally Financial's workforce. When I joined, platform adoption was at 9% of eligible employees — roughly 1 in 10 people who had access were using it. The platform existed but hadn't yet become a tool that business lines depended on or built with.

My mandate was to change that.

---

## The adoption problem

Low adoption wasn't a marketing problem. It was a product problem: the platform didn't yet solve enough real problems for enough real people to become habitual.

I started by treating the business lines as my users — not as stakeholders to align, but as customers to discover. Using a forward-deployed product model, I embedded with teams across business lines to understand their actual operational challenges before proposing any AI solutions. The question I kept asking: *what are you doing manually today that you shouldn't be?*

This discovery process surfaced the highest-value opportunities, separated them from the "that sounds cool but won't change how I work" ideas, and built the trust that made business lines want to partner on delivery.

---

## Scaling use cases: from 9 to 43

The first wave of production use cases had been delivered one-off, each requiring significant engineering support to build and onboard. That didn't scale.

I standardized the delivery process:

- **Reusable implementation patterns** for common use case types (document summarization, policy Q&A, workflow automation, structured data extraction)
- **Onboarding playbooks** that reduced time-to-first-use-case for new business lines by ~50%
- **No-code and low-code paths** that let business lines configure and extend solutions without waiting on engineering capacity

Result: scaled from 9 production AI use cases to 43, with 3x more teams shipping with minimal engineering support.

---

## Growing adoption: 9% → 21%

Adoption grew from 9% to 21% of eligible employees — 4,500+ monthly active users generating 346K+ prompts — not through a launch campaign, but through a product feedback loop:

1. **Telemetry → priorities:** I used platform telemetry (what features were being used, which use cases drove repeat visits, where drop-off happened) to identify what to build next. Adoption data informed roadmap decisions directly.
2. **High-impact capabilities:** Prioritized features that changed how business lines worked, not just features that were technically interesting.
3. **Business line champions:** Each new use case deployment created a team with a reason to use the platform regularly and advocate internally.

---

## AI governance as a product feature

Operating in a regulated financial services environment means risk and compliance aren't optional. I treated AI governance as a product requirement with the same rigor as any user-facing feature.

Key deliverables:
- **100% platform traffic coverage** with guardrails and LLM observability — every prompt and response on the platform goes through safety and compliance controls
- **Enterprise AI governance lifecycle** embedded into the delivery process — risk review, model risk management (MRM) approval, and controls documentation are part of how use cases ship, not a post-launch audit
- **Partnership with ERM and MRM** on risk framework design — so the governance layer is credible to risk stakeholders and workable for product teams

This made the platform trustworthy enough to scale. Business lines and executives didn't have to choose between moving fast and managing risk.

---

## Portfolio prioritization

As the use case pipeline grew, so did the intake volume. Not every idea deserved investment.

I led portfolio operating reviews that formalized how we screened, prioritized, and funded AI initiatives:
- Defined criteria for evaluating use cases: business value, technical feasibility, risk profile, strategic alignment
- Screened out ~30% of low-value initiatives before they consumed engineering capacity
- Concentrated investment on the 13+ strategic products representing 80%+ of portfolio value

I also shaped the multi-year AI roadmap — evaluating business priorities against emerging AI capabilities and developing executive decision frameworks that guided strategic AI investment and funding decisions.

---

## Key outcomes

| Metric | Result |
|---|---|
| Platform adoption | 9% → 21% of eligible employees |
| Monthly active users | 4,500+ |
| Prompts generated | 346K+ |
| Production AI use cases | 9 → 43 |
| Onboarding time reduction | ~50% |
| Teams shipping independently | 3x increase |
| Platform traffic with guardrails | 100% |
| Low-value initiatives screened | ~30% |

---

## What this taught me

**The forward-deployed model works.** Sitting inside a business line long enough to understand their real problems — not just their stated requests — produces better product decisions and faster adoption. The trust you build doing it also matters: business lines partner differently with a PM they've worked alongside than one who sends requirements docs.

**Governance done wrong kills velocity. Done right, it enables it.** The teams that resisted our governance process initially came around once they saw it as a path to deployment, not a barrier. When risk review is predictable and the checklist is clear, it's faster than ad hoc reviews.

**Portfolio discipline is a product skill.** Saying no to a legitimate use case because a better one deserves the investment is harder than it sounds inside a large organization with many stakeholders. Having a structured, defensible prioritization process is what makes it possible.
