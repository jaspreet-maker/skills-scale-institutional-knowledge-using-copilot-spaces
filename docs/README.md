# OctoAcme Project Management Docs

OctoAcme uses a lightweight project lifecycle designed to move work from idea to measurable outcomes with clear ownership and low overhead. Projects flow through five connected phases: **initiation** (problem framing, one-pager, stakeholders), **planning** (prioritized backlog, estimates, milestones, dependencies), **execution and tracking** (board-driven delivery and iteration), **release and deployment** (staged rollout and verification), and **retrospective/continuous improvement** (learning loops and follow-through). This keeps teams aligned on both delivery progress and customer impact.

Roles are intentionally clear to avoid handoff gaps. **Project Managers** coordinate delivery plans, risks, and communications; **Product Managers** define outcomes, prioritize scope, and track success metrics; **Developers** implement, test, and surface technical risks; **QA/Testing** validates acceptance criteria and release readiness; and **Stakeholders** provide direction, feedback, and approvals. Across phases, these roles collaborate around shared artifacts such as the one-pager, backlog, release plan, risk register, and retrospective action items.

Communication is structured around predictable cadences and transparent escalation. Teams use standups for short-term execution alignment, weekly delivery/risk syncs for cross-functional visibility, and stakeholder updates on a weekly or milestone basis. Status, decisions, and risks are maintained in a **single source of truth** (for example, project docs/board), while blockers and incidents follow a defined escalation path from team triage to Project Manager (PjM)-led escalation and sponsor/security escalation when business impact is high.

Quality assurance is embedded from development through release. OctoAcme favors small pull requests linked to issues and acceptance criteria, with CI checks (tests/linting) and security scans before merge approval. Validation typically includes unit tests for new logic, integration tests where needed, end-to-end smoke tests for critical flows, and manual QA for feature acceptance. Releases use pre-release criteria and deployment checklists (including rollback readiness), and retrospectives convert lessons learned into owned backlog actions.

## Where to start / Key docs

- [Project management overview](./octoacme-project-management-overview.md)
- [Project initiation](./octoacme-project-initiation.md)
- [Project planning](./octoacme-project-planning.md)
- [Execution and tracking](./octoacme-execution-and-tracking.md)
- [Risk management and communication](./octoacme-risks-and-communication.md)
- [Release and deployment](./octoacme-release-and-deployment.md)
- [Retrospective and continuous improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Roles and personas](./octoacme-roles-and-personas.md)
- [RACI and role handoffs](./octoacme-raci-and-handoffs.md)
- [Release readiness checklist](./octoacme-release-readiness-checklist.md)
