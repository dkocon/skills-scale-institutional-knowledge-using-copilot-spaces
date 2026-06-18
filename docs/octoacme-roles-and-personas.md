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

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.

---

## Additional Personas

To reduce ambiguity and improve delivery outcomes, add the following additional personas. Each entry includes a short responsibilities list and how they interact with other roles.

### Release/Deployment Engineer (Release Manager)
- Responsibilities:
  - Own release pipelines and release runbooks
  - Coordinate release windows and deployment approvals
  - Maintain rollback procedures and perform post-deploy verifications
  - Keep release notes and change logs current
- Interaction:
  - Works closely with PM and Dev leads to schedule releases
  - Coordinates with QA for sign-off and smoke tests
  - Engages Security for final approvals on security-sensitive releases
  - Notifies Support/On-call and monitors post-release health

### Technical Program Manager (TPM)
- Responsibilities:
  - Coordinate cross-team technical dependencies and integration plans
  - Maintain milestone timelines and run dependency tracking
  - Drive architectural decision tracking and risk mitigation for multi-team efforts
- Interaction:
  - Partners with Product Managers for prioritization and scope alignment
  - Works with Engineering Managers and Tech Leads for estimates and design
  - Coordinates with Project Managers to align schedules and communications

### UX Researcher / Designer (Research Lead)
- Responsibilities:
  - Plan and conduct user research and usability studies
  - Synthesize insights into design requirements and acceptance criteria
  - Validate designs with prototype testing and feedback loops
- Interaction:
  - Collaborates with PM to define user-centered success metrics
  - Hands off UX specs to Developers and QA with clear acceptance criteria
  - Informs Product decisions using research findings

### Data Analyst / Analytics Owner
- Responsibilities:
  - Define and validate success metrics and key signals
  - Instrument events and maintain dashboards for monitoring and experiments
  - Provide analysis for A/B tests and post-release evaluation
- Interaction:
  - Works with PM to define measurable outcomes
  - Collaborates with Developers to implement telemetry
  - Reports outcomes to Stakeholders and Product teams

### Security Engineer (Security Reviewer)
- Responsibilities:
  - Assess designs and code for security risks and compliance concerns
  - Ensure security checks are present in CI and sign off on security-sensitive changes
  - Participate in threat modeling and remediation planning
- Interaction:
  - Engages early in planning and design phases
  - Coordinates with Developers and Release Engineer to resolve findings
  - Reports critical risks to PM and Project Sponsor as needed

### QA Lead / Test Owner
- Responsibilities:
  - Define test strategy, test plans, and acceptance criteria ownership
  - Coordinate manual QA and automation efforts and test sign-off
  - Validate pre-release checks and smoke tests
- Interaction:
  - Works directly with Developers to improve test coverage
  - Communicates with PM on acceptance criteria and release readiness
  - Coordinates with Release Engineer for post-deploy verifications

### Support / On-call Lead
- Responsibilities:
  - Maintain runbooks and support playbooks for production incidents
  - Coordinate on-call rotations and escalation pathways
  - Triage post-release issues and provide operational feedback to engineering
- Interaction:
  - Receives pre-release notices from Release Engineer
  - Collaborates with PM and QA to understand known issues and mitigations
  - Reports recurring production issues to Project Manager and Product

---

## How to use these additions
- Add short "role cards" to the project README or a centralized People & Roles page linking to these definitions.
- Reference the relevant persona in acceptance criteria (e.g., "Security sign-off required from Security Reviewer").
- Use these definitions to populate reviewer lists on PR templates and to build pre-release checklists.
