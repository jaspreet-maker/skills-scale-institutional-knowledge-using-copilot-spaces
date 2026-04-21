# OctoAcme — RACI and Role Interaction Matrix

Use this lightweight matrix to clarify ownership and handoffs across the lifecycle.  
RACI = **R**esponsible (does the work), **A**ccountable (final owner), **C**onsulted, **I**nformed.

Role abbreviations used below:
- **Dev** = Developers
- **PdM** = Product Manager
- **PjM** = Project Manager
- **QA** = QA Lead
- **UX** = UX Designer
- **RM** = Release Manager
- **SE** = Support Engineer

| Activity | Dev | PdM | PjM | QA | UX | RM | SE |
| --- | --- | --- | --- | --- | --- | --- | --- |
| Acceptance criteria definition (Planning) | C | A/R | C | C | C | I | I |
| Definition of Done (Planning) | R | C | A | C | C | I | I |
| Test strategy and sign-off (Execution/Release) | C | I | C | A/R | I | C | I |
| Release go/no-go (Release) | C | C | C | C | I | A/R | I |
| Incident and escalation communications (Release/Operations) | C | I | A | C | I | R | R |
| Retro action item ownership (Retro) | R | C | A | C | C | C | C |

## Handoff notes for critical points

### 1) Acceptance criteria definition
- **Primary handoff:** PdM -> Dev + QA + UX
- PdM finalizes business intent and acceptance outcomes.
- Dev and QA confirm feasibility/testability; UX confirms usability expectations.

### 2) Definition of Done (DoD)
- **Primary handoff:** PjM + Dev -> Team
- PjM maintains the shared DoD baseline.
- Dev proposes technical completion gates; QA/PdM provide quality/outcome input.

### 3) Test strategy and sign-off
- **Primary handoff:** QA -> RM + PjM
- QA consolidates quality evidence and recommends sign-off status.
- RM and PjM use this input to manage release readiness and communication.

### 4) Release go/no-go
- **Primary handoff:** RM -> Stakeholders
- RM runs the go/no-go checkpoint with QA, Dev, PjM, and PdM inputs.
- RM communicates final decision and timeline.

### 5) Incident/escalation communications
- **Primary handoff:** SE + RM -> PjM (major risk) -> Stakeholders
- SE handles first-line intake and customer-facing updates.
- RM coordinates release-context incident handling; PjM leads broader escalation.

### 6) Retro action ownership
- **Primary handoff:** Team -> PjM tracking -> Role owners
- PjM records owners and due dates; actions are assigned to the most relevant function.
