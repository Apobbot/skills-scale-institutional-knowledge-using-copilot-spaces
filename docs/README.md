# OctoAcme Project Management Docs

This directory contains OctoAcme's shared project management processes. Use these documents to start, plan, execute, release, communicate about, and improve a project. Detailed guidance is maintained in the linked documents and should remain the source of truth.

## Project Management Process Summary

OctoAcme uses a customer-first, cross-functional, and iterative delivery model with clear ownership. Projects begin with initiation, where teams confirm the business problem, measurable success criteria, stakeholders, timeline, resources, and initial risks. Planning converts approved work into a prioritized and estimated backlog with acceptance criteria, a Definition of Done, dependencies, milestones, and a release plan.

During execution, named Project Managers and Product Leads coordinate delivery, priorities, risks, and communications while Developers and QA/Testing implement and validate the work. Teams use a GitHub project board, regular standups and delivery syncs, demos or reviews, small pull requests, and CI-based testing and linting. Risks are tracked in a register, statuses are communicated through consistent templates and escalation paths, and quality is supported by unit, integration, end-to-end, security, and manual testing as appropriate.

Releases follow documented pre-release and deployment checklists, including passing CI and security checks, staging smoke tests, rollback planning, release notes, and post-deployment verification. Each sprint, release, incident, or important milestone concludes with a retrospective that turns lessons into owned, dated action items. These improvements are tracked through the backlog and reviewed regularly for measurable impact.

## Process Documents

- [Project Management Overview](octoacme-project-management-overview.md) — Principles, roles, lifecycle, artifacts, and communication cadence.
- [Project Initiation](octoacme-project-initiation.md) — Validate a proposal and decide whether it is ready for planning.
- [Project Planning](octoacme-project-planning.md) — Define scope, backlog, estimates, milestones, dependencies, and quality approach.
- [Execution and Tracking](octoacme-execution-and-tracking.md) — Manage day-to-day delivery, workflows, quality, metrics, and blockers.
- [Risk Management and Communication](octoacme-risks-and-communication.md) — Maintain risks and dependencies and standardize stakeholder communication.
- [Release and Deployment](octoacme-release-and-deployment.md) — Prepare, deploy, verify, communicate, and roll back releases.
- [Retrospective and Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track improvement actions.
- [Roles and Personas](octoacme-roles-and-personas.md) — Understand the responsibilities and goals of Developers, Product Managers, and Project Managers.

## Navigation Conventions

- Keep this README in `docs/` as the entry point for the process knowledge base.
- Link directly to Markdown documents using relative paths.
- Update this index whenever a process document is added, renamed, or removed.
- Keep lifecycle summaries brief here and place detailed policies, templates, checklists, and examples in the linked documents.
