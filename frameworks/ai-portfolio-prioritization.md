# Enterprise AI Intake & Portfolio Prioritization

A framework I developed and use at Ally Financial for managing a high-volume AI opportunity pipeline inside a large organization.

The core problem it solves: when a GenAI platform is available to the whole enterprise, every business line wants to build something. Most of those ideas are not bad — they're just not worth the investment compared to the alternatives. The intake and prioritization process is how you avoid building 40 mediocre things instead of 13 high-value ones.

---

## The problem with most AI intake processes

Most enterprise AI intake processes fail in one of two ways:

1. **Too open:** Every idea gets logged. Backlog grows. No one has the authority to kill anything. Engineering gets pulled in every direction and nothing ships at depth.
2. **Too closed:** A small committee approves ideas based on executive sponsorship, not business value. Safe, visible ideas win. High-value operational ideas from the middle of the org get deprioritized.

The framework below tries to fix both.

---

## Stage 1: Opportunity intake (before any resourcing)

Every incoming idea gets a structured intake form that captures:

- **Problem statement** (what is the manual or broken process today?)
- **Affected users** (who does this problem, how often, at what volume?)
- **Business line sponsor** (who owns the outcome, not just the idea?)
- **Rough success criteria** (what does better look like, in measurable terms?)
- **Preliminary risk flags** (data sensitivity, regulatory surface, model risk triggers)

This isn't bureaucracy — it's how you filter out "wouldn't it be cool if..." from "here's a real operational problem with a real owner." An idea without a business line sponsor and a measurable outcome doesn't proceed.

---

## Stage 2: Scoring and triage

Scored on four dimensions:

| Dimension | What I'm assessing |
|---|---|
| **Business value** | Revenue impact, cost reduction, time savings — quantified where possible |
| **Strategic alignment** | Does this reinforce a platform capability, serve a priority segment, or advance a multi-year roadmap theme? |
| **Feasibility** | Is this solvable with the platform's current capabilities, or does it require net-new infrastructure? |
| **Risk profile** | Regulatory exposure, data sensitivity, MRM review requirements, reputational risk |

High-value, low-risk, feasible ideas with strategic alignment get fast-tracked. High-value ideas with elevated risk get triaged through governance first. Low-value ideas get parked or killed.

I screen out ~30% of ideas at this stage — not because they're bad, but because the portfolio can't absorb them all and better ideas deserve the investment.

---

## Stage 3: Portfolio view and investment decisions

Before resourcing anything, I look at the full portfolio:

- **Concentration:** Are we over-indexed on one business line, one use case type, or one risk tier?
- **Coverage vs. depth:** Are we spreading too thin, or are we building enough capability depth in the highest-value areas?
- **Dependency mapping:** Which use cases share infrastructure, data, or governance components? Sequencing matters.

The goal is to ensure the 13 things we build represent 80%+ of the portfolio value — not to build everything that crosses a quality threshold.

---

## Stage 4: Governance pre-flight

Before any use case enters active development, it completes a pre-flight checklist:

- Risk classification confirmed
- MRM review path identified (if applicable)
- Data handling requirements documented
- Guardrails and observability requirements specified
- Success metrics agreed upon with business line sponsor

This is not a gate that slows teams down — it's a map that prevents the expensive stops later. Use cases that skip this step reliably run into governance blockers mid-build.

---

## What this produces

- A pipeline where every active use case has a clear owner, measurable success criteria, and a governance path
- A portfolio that is concentrated on value, not spread across every request
- A shared language between product, engineering, risk, and business line stakeholders about why things are prioritized the way they are
- A screening process that is defensible to executives and respectful of the teams whose ideas don't make the cut

---

## When this breaks down

This framework assumes a business line sponsor who will stay engaged through delivery. When sponsorship is nominal — someone approved an idea but isn't willing to commit time or change management resources — the use case tends to fail at adoption even if it ships. I've learned to treat active sponsor engagement as a hard requirement, not a nice-to-have.
