# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Naming and abbreviations used across docs

To avoid ambiguity:
- **Product Manager (PdM)** = owns product outcomes, prioritization, and customer value.
- **Project Manager (PjM)** = owns delivery planning, execution coordination, and status/risk communication.
- Avoid using just **"PM"** in process docs because it can mean either role.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with Project Manager (PjM) and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## QA Lead

### Role Summary
QA Leads own the quality strategy across the delivery lifecycle. They ensure testing is risk-based, traceable to acceptance criteria, and aligned to release confidence.

### Responsibilities
- Define and maintain the overall test strategy and quality gates
- Align test plans to acceptance criteria and Definition of Done (DoD)
- Coordinate manual and automated validation across feature areas
- Provide quality sign-off input for release go/no-go decisions
- Track defect trends and recommend process improvements

### Goals
- Prevent escaped defects in critical workflows
- Improve release confidence and predictability
- Make quality expectations explicit and repeatable

### Typical Communication
- Test strategy reviews with Developers, Product Manager (PdM), and Project Manager (PjM)
- Quality status updates in sprint/release syncs
- Defect triage summaries and sign-off recommendations

### Lifecycle interactions
- **Initiation**: Advises on quality risks for proposed scope.
- **Planning**: Partners with PdM and Developers on acceptance criteria and DoD quality gates.
- **Execution**: Coordinates test execution and defect triage with Developers; reports status to PjM.
- **Release**: Provides test sign-off recommendation to Release Manager and PjM.
- **Retrospective**: Shares quality metrics and corrective actions with the full team.

---

## UX Designer

### Role Summary
UX Designers ensure solutions are usable, accessible, and aligned with user needs from concept to release.

### Responsibilities
- Translate user problems into flows, wireframes, and interaction guidance
- Run or support lightweight user research and usability validation
- Partner with PdM on problem framing and acceptance outcomes
- Provide design specifications and implementation clarifications to Developers
- Validate delivered experience before release

### Goals
- Reduce usability friction and rework
- Improve task completion and user satisfaction outcomes
- Keep design decisions consistent and evidence-based

### Typical Communication
- Discovery/planning workshops with PdM and PjM
- Design reviews with Developers
- Usability findings and recommendations shared with stakeholders

### Lifecycle interactions
- **Initiation**: Helps frame user problems and success criteria with PdM.
- **Planning**: Defines UX acceptance expectations with PdM and Developers.
- **Execution**: Clarifies design intent during implementation and review.
- **Release**: Supports final UX validation in release readiness checks.
- **Retrospective**: Contributes user-feedback themes for follow-up actions.

---

## Release Manager

### Role Summary
Release Managers coordinate release readiness and deployment execution to ensure low-risk, well-communicated production changes.

### Responsibilities
- Own release calendar, sequencing, and deployment coordination
- Confirm completion of release prerequisites and rollback readiness
- Lead release go/no-go decisions with QA Lead, PjM, and technical owners
- Coordinate release communications to stakeholders and Support Engineer
- Track release outcomes and post-release follow-up items

### Goals
- Deliver predictable, low-risk releases
- Minimize deployment-related incidents and downtime
- Ensure clear ownership during release events

### Typical Communication
- Release readiness checkpoints and go/no-go meetings
- Deployment timeline updates and stakeholder announcements
- Post-release status reports and issue escalations

### Lifecycle interactions
- **Initiation**: Flags release constraints for major initiatives.
- **Planning**: Partners with PjM on milestone/release sequencing.
- **Execution**: Tracks readiness signals across Developers and QA Lead.
- **Release**: Leads operational coordination and final go/no-go decision framing.
- **Retrospective**: Documents release lessons and process improvements.

---

## Support Engineer

### Role Summary
Support Engineers own frontline incident/issue intake and customer-impact communication, creating a feedback loop from production back into planning.

### Responsibilities
- Triage incoming incidents, bugs, and customer-reported issues
- Provide first-line diagnostics and escalation context to engineering teams
- Maintain support-facing release notes and known-issues updates
- Communicate incident status and workarounds to affected stakeholders
- Feed recurring issue trends into backlog and retrospective discussions

### Goals
- Reduce mean time to acknowledge and resolve customer-impacting issues
- Improve clarity and consistency of support communications
- Turn support insights into actionable product/process improvements

### Typical Communication
- Incident channel updates with Developers, QA Lead, and Release Manager
- Customer/support-facing status updates and workaround guidance
- Recurring issue summaries to PdM and PjM

### Lifecycle interactions
- **Initiation**: Shares historical issue patterns that influence scope decisions.
- **Planning**: Provides support-readiness input for launch plans and known risks.
- **Execution**: Validates support docs/known issues for in-flight features.
- **Release**: Coordinates launch comms and early-life incident handling with Release Manager.
- **Retrospective**: Brings production pain points and escalation metrics to action planning.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
