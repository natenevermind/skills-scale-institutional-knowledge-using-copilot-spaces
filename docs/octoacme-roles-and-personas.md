# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

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
- Weekly alignment with PM and engineering leads
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

## Business Analysts

### Role Summary
Business Analysts translate stakeholder needs into clear, validated requirements and acceptance criteria. They connect business intent with delivery work and help ensure the solution solves the intended problem.

### Responsibilities
- Elicit, analyze, prioritize, and document requirements
- Clarify business rules, dependencies, and process impacts
- Develop and validate acceptance criteria with stakeholders
- Support backlog refinement and trace requirements to outcomes
- Identify gaps or inconsistencies between stakeholder expectations and proposed solutions

### Decision and Escalation Authority
Business Analysts recommend requirement priorities and clarify ambiguity, but do not independently change approved scope or commitments. They escalate unresolved conflicts, unclear ownership, or scope changes to the Product Manager and Project Manager.

### Interactions with Existing Roles
- Partners with the **Product Manager** to refine problem statements, priorities, and success measures.
- Works with the **Project Manager** to record dependencies, scope decisions, and delivery impacts.
- Collaborates with **Developers** and **QA** to ensure requirements and acceptance criteria are implementable and testable.
- Brings stakeholder needs and feedback into planning and validation activities.

### Handoff Expectations
The Business Analyst provides approved requirements, open questions, and traceable acceptance criteria to delivery teams. Confirmed changes are documented and communicated before teams include them in their plans.

---

## Change and Adoption Leads

### Role Summary
Change and Adoption Leads plan and coordinate the people-side of a project. They prepare affected teams and stakeholders to understand, adopt, and sustain the delivered change.

### Responsibilities
- Assess stakeholder impact and readiness
- Create communication, training, and adoption plans
- Coordinate pilots, feedback sessions, and rollout support
- Track adoption milestones and resistance or readiness risks
- Recommend adjustments to rollout or enablement activities

### Decision and Escalation Authority
Change and Adoption Leads decide how to execute approved change activities and recommend rollout readiness. They escalate unresolved stakeholder risks, go-live concerns, or unsupported adoption commitments to the Project Manager and sponsor or stakeholder leadership.

### Interactions with Existing Roles
- Works with the **Project Manager** to align rollout schedules, dependencies, communications, and risks.
- Partners with the **Product Manager** on customer outcomes, release messaging, and feedback.
- Coordinates with **Customer Success Representatives** and team leads to deliver enablement and gather adoption signals.
- Gives Developers and Support teams release-readiness and known-user-impact information.

### Handoff Expectations
The Change and Adoption Lead provides approved communications, training materials, readiness assessments, and support plans before rollout. After launch, adoption feedback and outstanding risks are handed to Product, Support, and Customer Success.

---

## Security Leads

### Role Summary
Security Leads establish security requirements and provide specialist guidance for project risks. They help teams design, build, test, and release within the organization's security standards.

### Responsibilities
- Define relevant security requirements and review security risks
- Assess threat models, vulnerabilities, and exception requests
- Advise on secure design and implementation practices
- Coordinate required security testing and evidence
- Track remediation ownership and release-blocking security issues

### Decision and Escalation Authority
Security Leads approve or reject work within their delegated security authority and may block release where a mandatory control or unresolved critical risk is not met. Exceptions and unresolved high-risk findings are escalated through established security governance.

### Interactions with Existing Roles
- Works with **Developers** and **QA** on secure implementation and validation.
- Shares risks and required mitigations with the **Project Manager** for scheduling and escalation.
- Coordinates with the **Product Manager** on security trade-offs and customer impact.
- Collaborates with Operations/Support and Compliance/Privacy Leads for incident readiness and control requirements.

### Handoff Expectations
The Security Lead documents required controls, risk decisions, exception owners, remediation actions, and release conditions. Residual risks and follow-up actions are handed to the accountable delivery or operations owner.

---

## Compliance and Privacy Leads

### Role Summary
Compliance and Privacy Leads identify regulatory, contractual, and privacy obligations that affect project scope and delivery. They ensure required controls are considered and documented.

### Responsibilities
- Interpret applicable compliance and privacy requirements
- Assess project activities, data handling, and control impacts
- Recommend safeguards and required approvals
- Review or escalate exceptions and policy conflicts
- Maintain evidence and communication for compliance decisions

### Decision and Escalation Authority
Compliance and Privacy Leads determine whether a project is aligned with their compliance mandate and may require changes or escalate unresolved obligations. Approval, exception, and legal decisions follow the organization's formal governance processes.

### Interactions with Existing Roles
- Coordinates with **Security Leads** on security controls and risk evidence.
- Works with **Product Managers** and **Developers** to shape data use, consent, retention, and product requirements.
- Partners with the **Project Manager** to track approvals, dependencies, evidence, and deadlines.
- Consults Legal and stakeholder representatives when obligations or interpretations require escalation.

### Handoff Expectations
The Compliance and Privacy Lead provides control requirements, approvals or denials, exception records, and evidence expectations. Delivery teams receive clear actions and owners, and unresolved matters are escalated before launch commitments are confirmed.

---

## Customer Success Representatives

### Role Summary
Customer Success Representatives represent customer adoption and ongoing value. They provide delivery teams with direct customer feedback and help validate that outcomes are usable and achievable in practice.

### Responsibilities
- Share customer needs, risks, and feedback with delivery teams
- Validate rollout assumptions and customer readiness
- Support adoption planning and communicate known issues
- Track customer outcomes and early success signals
- Escalate high-impact adoption or satisfaction risks

### Decision and Escalation Authority
Customer Success Representatives recommend prioritization and escalation based on customer impact, but do not change product scope or delivery commitments unilaterally. Significant risks or unmet customer commitments are escalated to the Product Manager and Project Manager.

### Interactions with Existing Roles
- Provides customer insight and feedback to the **Product Manager** and delivery team.
- Works with the **Project Manager** on customer-facing milestones, readiness, and escalations.
- Partners with **Change and Adoption Leads** on enablement and rollout activities.
- Coordinates with Support and Operations on known issues and customer impact.

### Handoff Expectations
The Customer Success Representative communicates validated customer needs, rollout readiness, and adoption findings. Post-launch feedback and customer commitments are handed to Product, Support, and the Change and Adoption Lead for follow-up.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

