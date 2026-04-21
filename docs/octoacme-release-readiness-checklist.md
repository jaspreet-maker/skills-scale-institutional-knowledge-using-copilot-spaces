# OctoAcme — Release Readiness Checklist

Use this checklist during execution and before deployment to confirm quality, ownership, and communication readiness.  
See also: [Release & Deployment Guide](./octoacme-release-and-deployment.md), [Roles and Personas](./octoacme-roles-and-personas.md), [RACI and Handoffs](./octoacme-raci-and-handoffs.md).

## Ownership guide
- **Release Manager (RM):** Accountable for release coordination and go/no-go.
- **QA Lead (QA):** Accountable for quality evidence and sign-off recommendation.
- **Project Manager (PjM):** Accountable for cross-team status/risk communication.
- **Support Engineer (SE):** Responsible for incident intake readiness and support messaging.

## Checklist

### 1) Scope and acceptance (Planning -> Execution)
- [ ] Scope for this release is frozen and linked to approved issues/PRs.
- [ ] Acceptance criteria are complete and traceable for included changes.
- [ ] Definition of Done (DoD) checks are met for all included backlog items.

### 2) Quality and test confidence (Execution -> Release)
- [ ] QA Lead has reviewed the test strategy for release risk level.
- [ ] Critical-path tests (unit/integration/smoke) are passing.
- [ ] Open defects are triaged; release blockers are resolved or explicitly waived.
- [ ] QA Lead provides a documented sign-off recommendation (go / conditional go / no-go).

### 3) Deployment safety (Release)
- [ ] Release Manager confirms deployment window, owners, and sequencing.
- [ ] Rollback/mitigation plan is documented and validated.
- [ ] Observability checks are defined (logs, alerts, dashboards, key metrics).
- [ ] Post-deploy verification steps and owners are assigned.

### 4) Communication and support readiness (Release -> Operations)
- [ ] Release notes are drafted and reviewed.
- [ ] Stakeholder communication plan is ready (who/what/when/channel).
- [ ] Support Engineer has known issues, workarounds, and escalation contacts.
- [ ] Incident channel/on-call coverage is confirmed for release window.

### 5) Go/No-Go decision record
- [ ] Go/no-go meeting held with RM, QA, Dev lead, PdM, and PjM.
- [ ] Final decision and rationale recorded in release notes/project log.
- [ ] Follow-up actions (if conditional go) are assigned owners and due dates.
