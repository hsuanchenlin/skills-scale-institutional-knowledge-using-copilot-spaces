# OctoAcme — Decision Log Template

## Purpose
Provide a lightweight, consistent format for recording significant project decisions so that context, rationale, and accountability are preserved throughout the project lifecycle.

## When to Log a Decision
Record a decision entry when:
- A trade-off with notable project impact is made (scope, timeline, architecture, resourcing)
- Multiple options were considered and one was chosen
- A stakeholder or sponsor decision is required or has been given
- A decision reversal or update needs to be tracked

---

## Decision Entry Template

Use one entry per decision. Copy this block for each new decision.

```
### Decision [ID] — [Short Title]

| Field           | Detail |
|-----------------|--------|
| Date            | YYYY-MM-DD |
| Status          | Proposed / Approved / Superseded |
| Decision Owner  | Name or Role |
| Stakeholders    | Names or roles who were consulted or informed |

**Context**
Briefly describe the situation or problem that required a decision.

**Options Considered**
1. Option A — brief description and trade-offs
2. Option B — brief description and trade-offs
3. (Add more if applicable)

**Decision**
State the chosen option clearly.

**Rationale**
Explain why this option was selected over the alternatives.

**Consequences / Follow-on Actions**
- List any resulting tasks, risks, or dependencies
- Note if this decision supersedes a prior decision (reference its ID)

**Escalation Path (if applicable)**
Describe the escalation path if this decision needs to be revisited (e.g., if new information emerges).
```

---

## Example Decision Entry

### Decision 001 — Adopt Incremental Release Strategy

| Field           | Detail |
|-----------------|--------|
| Date            | 2024-03-15 |
| Status          | Approved |
| Decision Owner  | Project Manager |
| Stakeholders    | Product Manager, Engineering Manager, Sponsor |

**Context**
The initial plan called for a single large release at the end of Q2, but growing scope and integration risks made this approach high-risk.

**Options Considered**
1. Single big-bang release at Q2 end — simpler scheduling, but high deployment risk and late feedback.
2. Incremental milestone releases every 4 weeks — more coordination overhead, but earlier feedback and reduced deployment risk.

**Decision**
Adopt incremental milestone releases every 4 weeks.

**Rationale**
Incremental releases reduce integration risk, allow earlier stakeholder validation, and provide faster feedback loops aligned with OctoAcme's iterative delivery principles.

**Consequences / Follow-on Actions**
- Update release plan and milestone map in project planning doc
- Schedule release ceremonies for each milestone
- Adjust QA cadence to align with 4-week release cycles

**Escalation Path (if applicable)**
If scope growth requires extending a milestone, the Project Manager escalates to the Product Manager and Sponsor within 48 hours of identification.

---

## Decision Log Index

Maintain an index of all logged decisions for quick reference.

| ID  | Title                            | Date       | Status    | Owner           |
|-----|----------------------------------|------------|-----------|-----------------|
| 001 | Adopt Incremental Release Strategy | 2024-03-15 | Approved | Project Manager |
| _Add new rows as decisions are logged_ | | | | |

---

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md) — for decision owners and stakeholder definitions
- [Handoff Checklist](./octoacme-handoff-checklist.md) — decisions may trigger handoff actions
- [Risks and Communication](./octoacme-risks-and-communication.md) — escalation paths and risk register
- [Project Planning](./octoacme-project-planning.md) — decisions that affect scope or milestones
