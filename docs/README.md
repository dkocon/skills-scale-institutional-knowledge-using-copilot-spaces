# OctoAcme Project Management Docs

This directory contains OctoAcme's project management processes and templates. This README provides a brief summary of OctoAcme's approach to project delivery and direct links to the full documents to help teammates find guidance quickly.

## OctoAcme Project Management Overview

OctoAcme follows a structured lifecycle approach to project delivery, consisting of five key phases: **Initiation, Planning, Execution, Release, and Close & Retrospective**. The process begins with an initiation gate where new ideas are validated through a lightweight Project One-pager that confirms business need, identifies stakeholders, and establishes measurable success criteria. Once approved, the team moves into planning—breaking work into shippable increments, creating a prioritized backlog with clear acceptance criteria, estimating scope, and documenting the Definition of Done. This emphasis on upfront clarity ensures alignment across stakeholders and reduces scope creep before execution begins.

Execution and delivery are orchestrated through a clear rhythm of daily standups (15 minutes), weekly delivery syncs, and sprint-based iterations using GitHub Projects with standard workflow columns: Backlog, Ready, In Progress, In Review, QA, and Done. OctoAcme emphasizes small pull requests (≤400 lines when possible), automated CI/CD testing and linting, and mandatory peer review before merging. Quality assurance is embedded throughout, combining unit tests, integration tests, end-to-end smoke tests, and security scanning. The team tracks velocity and burndown metrics while monitoring success indicators from the Project One-pager, creating a data-informed feedback loop for continuous improvement.

Roles and responsibilities are clearly defined across three primary personas: **Product Managers** (who define what to build and prioritize outcomes), **Project Managers** (who coordinate delivery, manage risks, and facilitate communication), and **Developers** (who implement features with quality and collaborate on design). This separation of concerns ensures that customer value, execution efficiency, and technical excellence are all actively managed. Communication is structured through weekly PM-PdM syncs, twice-weekly standups, monthly stakeholder updates, and a clear escalation path (Team → PM → Product Lead → Sponsor) for blockers.

Risk management and continuous improvement are woven into every phase. OctoAcme maintains a risk register throughout execution, capturing ID, description, impact, likelihood, owner, and mitigation plans—reviewed regularly at weekly syncs. After each sprint, release, or milestone, the team conducts a retrospective to capture learnings (what went well, what could improve) and convert them into tracked action items with owners and due dates. This closed-loop approach—from initiation through retrospective—ensures that OctoAcme not only delivers reliably but also learns and refines its processes continuously.

## Process Documents

### Core Guidance
- **[Project Management Overview](./octoacme-project-management-overview.md)** — Introduction to OctoAcme's approach, core principles, roles, and lifecycle.
- **[Roles & Personas](./octoacme-roles-and-personas.md)** — Definitions and responsibilities for Project Managers, Product Managers, Developers, and QA.

### Project Lifecycle Phases

1. **[Project Initiation](./octoacme-project-initiation.md)** — Validate business need, confirm stakeholders, create a One-pager, and establish go/no-go criteria for planning.

2. **[Project Planning](./octoacme-project-planning.md)** — Break work into shippable increments, prioritize the backlog, estimate scope, define acceptance criteria, and create a release plan.

3. **[Execution & Tracking](./octoacme-execution-and-tracking.md)** — Manage day-to-day delivery with standups, project board workflow, PR conventions, CI checks, quality gates, and reporting.

4. **[Release & Deployment](./octoacme-release-and-deployment.md)** — Pre-release requirements, deployment checklist, rollback procedures, and release notes.

5. **[Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings after each sprint or milestone and convert them into actionable improvements.

### Cross-Cutting Concerns
- **[Risk Management & Communication](./octoacme-risks-and-communication.md)** — Risk register lifecycle, stakeholder communication templates, and escalation paths.

## Quick Reference

| Process | Purpose | Key Artifact |
|---------|---------|--------------|
| Initiation | Validate idea and align stakeholders | Project One-pager |
| Planning | Create actionable plan and backlog | Prioritized Backlog + Release Plan |
| Execution | Deliver features in sprints | Project Board + PRs |
| Release | Deploy to production safely | Release Notes + Deployment Checklist |
| Retrospective | Learn and improve | Action Items |

## How to Propose Changes

Use the **[Add Content to Project Management Process Docs](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)** issue template to suggest edits, new sections, or entirely new process documents.

When proposing updates, include:
- Summary of the new content or update
- Rationale for why it's needed
- Suggested content (if available)
- Confirmation that the update aligns with existing docs and closes a gap
