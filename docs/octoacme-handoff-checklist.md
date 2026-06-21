# OctoAcme — Cross-Functional Handoff Checklist

## Purpose
Ensure that work transferred between roles, teams, or lifecycle phases is complete, well-documented, and sets the receiving party up for success. Use this checklist at every significant handoff to reduce dropped context and rework.

## When to Use
- Handoff from planning to execution (kickoff)
- Handoff from development to QA/testing
- Handoff from QA/testing to release/deployment
- Handoff from project team to Customer Support/Success at release
- Any other significant cross-role or cross-team transition

---

## General Handoff Checklist (All Transitions)

- [ ] **Scope is clear:** The receiving party has read and acknowledged the acceptance criteria or deliverable definition
- [ ] **Owner identified:** A named owner is assigned for the receiving work
- [ ] **Dependencies documented:** Any outstanding dependencies or blockers are listed and have owners
- [ ] **Open decisions resolved:** No unresolved decisions that would block the receiving party's work (or decision is logged in the [Decision Log](./octoacme-decision-log-template.md) with an owner)
- [ ] **Artifacts accessible:** All relevant docs, specs, designs, or test plans are linked and accessible
- [ ] **Key contacts shared:** The receiving party knows who to contact for questions (and escalations)
- [ ] **Timeline agreed:** The receiving party has confirmed the expected timeline and any hard deadlines
- [ ] **Risks communicated:** Any known risks or concerns relevant to the handoff have been shared

---

## Planning → Execution Handoff

*Used when the project moves from planning into active development.*

- [ ] Project One-pager and Charter reviewed and approved
- [ ] Prioritized backlog with acceptance criteria available
- [ ] Definition of Done (DoD) shared with the full delivery team
- [ ] Release plan and milestone map confirmed
- [ ] Repository and project board set up and accessible
- [ ] CI/CD pipeline configured (coordinate with DevOps/SRE)
- [ ] Initial risk register shared with Engineering Manager and QA
- [ ] QA/Testing has reviewed the test plan and environment requirements
- [ ] All team members are onboarded and have access to required tools

---

## Development → QA / Testing Handoff

*Used when a feature or fix is ready for QA validation.*

- [ ] All acceptance criteria met and documented in the PR or issue
- [ ] PR merged to the appropriate branch with CI passing
- [ ] Build deployed to the test environment (coordinate with DevOps/SRE)
- [ ] Test data or test accounts set up and accessible to QA
- [ ] Known limitations or out-of-scope items are noted for QA
- [ ] Developer available for questions or quick fixes during QA window
- [ ] Linked issues and related test cases referenced in the PR or handoff note

---

## QA / Testing → Release Handoff

*Used when QA has completed testing and the release is ready to proceed.*

- [ ] All in-scope test cases executed and results documented
- [ ] Release-blocking defects resolved and re-verified
- [ ] Known issues documented with severity assessment and acceptance from Product Manager
- [ ] QA sign-off recorded (in issue tracker, release doc, or project board)
- [ ] Release notes reviewed and accurate
- [ ] Rollback plan documented and reviewed by DevOps/SRE
- [ ] Release checklist in [Release and Deployment](./octoacme-release-and-deployment.md) completed
- [ ] Stakeholders notified of release readiness

---

## Release → Customer Support / Success Handoff

*Used when a release is deployed to production and the team transitions to support mode.*

- [ ] Release notes published and shared with Customer Support/Success
- [ ] Customer-facing documentation and FAQs updated
- [ ] Known issues communicated to Customer Support/Success with workarounds (if any)
- [ ] Monitoring dashboards and alerts confirmed active (coordinate with DevOps/SRE)
- [ ] On-call rotation and escalation path confirmed for post-release period
- [ ] Internal announcement sent to relevant stakeholders
- [ ] Data Analyst notified to begin tracking success metrics post-launch

---

## Post-Handoff Checklist

After the handoff is complete, confirm:

- [ ] Receiving party has acknowledged receipt and reviewed all materials
- [ ] Open items or outstanding actions are captured in the project board or issue tracker
- [ ] Any decisions made during the handoff are recorded in the [Decision Log](./octoacme-decision-log-template.md)
- [ ] Handoff outcome (smooth / issues found) noted for retrospective

---

## Related Documents
- [Roles and Personas](./octoacme-roles-and-personas.md) — for role definitions and interaction points
- [Decision Log Template](./octoacme-decision-log-template.md) — for capturing decisions made during or triggered by handoffs
- [Execution and Tracking](./octoacme-execution-and-tracking.md) — blocker escalation and execution checklist
- [Release and Deployment](./octoacme-release-and-deployment.md) — release checklist and rollback playbook
- [Risks and Communication](./octoacme-risks-and-communication.md) — escalation paths and communication templates
