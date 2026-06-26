# Discovery in a Regulated Environment

Standard product discovery assumes you can move fast: run interviews, prototype quickly, test with users, iterate. In regulated industries — financial services, healthcare, anything touching sensitive data or model risk — that process runs into real constraints.

This doc captures how I've adapted discovery practice for environments where compliance is a first-class concern.

---

## What changes in a regulated environment

**Data access for research is constrained.** You can't always show users a prototype that touches real customer data. Observation studies may require legal review. Interview recordings may be restricted.

**Stakeholders include risk and compliance, not just business lines.** A product direction that business stakeholders love can be blocked by risk if it wasn't shaped with them early. They're not obstacles — they're customers.

**The definition of "feasible" is more complex.** Technical feasibility is necessary but not sufficient. A feature might be technically buildable but require regulatory approval, model risk review, or legal sign-off that changes the timeline or the shape of what ships.

**Failure modes carry higher stakes.** In consumer financial services, a bad AI recommendation isn't just a bad user experience — it can be a compliance violation. Discovery needs to surface these stakes, not avoid them.

---

## How I adapt discovery

**Bring risk into problem framing, not just solution review**

I include an ERM or MRM stakeholder in the discovery phase — not to approve anything, but to help identify the constraint landscape early. Questions like "what data can we use?", "what decisions can the system make autonomously?", and "what does audit documentation look like for this?" are better asked during discovery than during build.

**Use proxies when direct user research is restricted**

When I can't observe users working with real data, I use:
- Process documentation and workflow maps as proxies for observation
- Support tickets, error logs, and operational metrics as proxies for user pain
- Subject matter experts (often former practitioners in the business line) as proxies for end users in early-stage research

These are imperfect substitutes. I'm explicit about that and design follow-up research to close the gaps as access opens up.

**Scope pilots with compliance in mind from day one**

When the discovery output is a pilot proposal, I include the compliance and data handling requirements in the pilot scope — not as appendices, but as core design decisions. A pilot that discovers a compliance blocker halfway through is a failed pilot.

**Write problem statements that include the constraint**

Instead of "users need faster access to customer financial history," I write "users need faster access to customer financial history within the existing data access controls and audit trail requirements." The constraint is part of the problem, not a postscript to it.

---

## What good regulated discovery produces

- A problem statement that includes the risk and compliance constraint, not just the user need
- A set of solution directions that are evaluated against feasibility, regulatory exposure, and MRM risk — not just user value
- Early alignment with risk and compliance stakeholders on what's in scope for a pilot
- A set of open questions that need answers before development starts (including questions for legal, compliance, or MRM)

---

## The underlying principle

In any environment, discovery is about reducing the cost of being wrong. In regulated environments, the cost of being wrong includes regulatory risk, legal exposure, and reputational harm — not just user churn or a bad NPS score. Discovery that doesn't surface those risks isn't thorough discovery; it's incomplete discovery.

The goal isn't to slow down. It's to make the right bets faster by knowing the full landscape before you commit.
