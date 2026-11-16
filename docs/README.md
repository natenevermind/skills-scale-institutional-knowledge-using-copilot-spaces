# OctoAcme Project Management Docs

This directory contains OctoAcme's project management processes, roles, and working guidance. Together, these documents describe a customer-first, iterative lifecycle for delivering product features, services, and integrations.

## Process overview

OctoAcme begins by validating a project's business need, measurable outcomes, stakeholders, initial risks, and resource needs. An approved initiative moves into planning, where the team agrees on scope, prioritizes and estimates backlog items, defines acceptance criteria and a Definition of Done, and maps milestones, dependencies, and a test approach.

During execution, the team tracks work on a project board, delivers in small increments, and uses pull requests linked to issues and acceptance criteria. Developers implement and test the work; the Product Manager owns outcomes and backlog priorities; the Project Manager coordinates delivery, risks, schedules, and communication; QA validates quality and acceptance; and stakeholders provide input and approvals. Regular standups, delivery syncs, and stakeholder updates keep progress, blockers, risks, and decisions visible. Risks and dependencies are tracked with owners and mitigations, and escalated through the agreed path when needed.

Quality is built into delivery through unit and applicable integration tests, CI tests and linting, security scanning, smoke tests for critical flows, and manual QA when needed. Before release, acceptance criteria and checks should pass, release notes and smoke tests should be ready, and rollback or mitigation plans should be documented. After a sprint, release, milestone, or incident, the team reflects, assigns owners and due dates to improvement actions, and follows up on their impact.

## Process documents

- [Project Management Overview](octoacme-project-management-overview.md) — lifecycle, principles, roles, artifacts, and communication cadence.
- [Project Initiation Guide](octoacme-project-initiation.md) — validate and authorize new work, align stakeholders, and prepare the one-pager.
- [Project Planning](octoacme-project-planning.md) — shape approved work into an estimated backlog, milestones, and delivery plan.
- [Execution & Tracking](octoacme-execution-and-tracking.md) — manage day-to-day delivery, PR workflow, quality checks, metrics, and blocker escalation.
- [Risk Management & Communication](octoacme-risks-and-communication.md) — maintain the risk register, communicate status, and escalate issues.
- [Release & Deployment](octoacme-release-and-deployment.md) — prepare, deploy, verify, announce, and roll back releases when necessary.
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — capture learnings and track improvement actions.
- [Roles & Personas](octoacme-roles-and-personas.md) — responsibilities, goals, and typical communication for key project roles.
