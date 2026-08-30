# OctoAcme Project Management Documentation

## Welcome
This folder contains the OctoAcme project management process documentation. Use these guides to understand how we run projects, manage risks, and deliver value.

## OctoAcme Approach
OctoAcme follows a structured, iterative project management methodology built on principles of customer focus, clear ownership, data-informed decisions, and psychological safety. Work progresses through five high-level phases: Initiation, Planning, Execution, Release, and Continuous Improvement. Each phase has associated artifacts, roles, and ceremonies to keep delivery predictable and aligned with business goals.

## Key Workflows
- Initiation: Capture the problem, goals, success metrics, stakeholders, and a high-level timeline in a Project One-pager. Move to planning only when success metrics and stakeholder alignment are confirmed.
- Planning: Break approved initiatives into shippable backlog items, estimate scope, identify dependencies and risks, and produce a release and milestone plan.
- Execution: Use a project board (Backlog, Ready, In Progress, In Review, QA, Done), timeboxed sprints, and a pull request workflow that favors small PRs, CI checks, and at least one approval before merging.
- Release: Follow pre-release checks (CI, security scans, release notes), staging smoke tests, automated production deployments where possible, and a documented rollback plan.
- Continuous Improvement: Run retrospectives after sprints or releases, convert action items into backlog issues, and measure the impact of improvements.

## Roles & Personas
- Product Manager (PdM): Owns product vision, success metrics, and backlog prioritization.
- Project Manager (PM): Coordinates delivery, schedules, risk management, and stakeholder communication.
- Developers: Implement features, write tests, and participate in code reviews.
- QA/Testing: Validate acceptance criteria, run manual and automated tests, and sign off on releases.

## Communication & Cadence
- Daily standups for progress and blockers
- Weekly delivery sync to review progress, risks, and cross-team dependencies
- PM + PdM weekly alignment
- Monthly stakeholder updates and ad-hoc escalations as needed
- Escalation path: Team -> PM -> Product Lead -> Sponsor; Security incidents notify Security on-call

## Quality Assurance Practices
- Unit and integration tests required for new logic
- End-to-end smoke tests for critical flows before release
- Security scanning in CI and manual QA for acceptance when needed
- Release checklist with post-deploy verification and rollback steps

## Docs in this folder
- octoacme-project-management-overview.md
- octoacme-project-initiation.md
- octoacme-project-planning.md
- octoacme-execution-and-tracking.md
- octoacme-risks-and-communication.md
- octoacme-release-and-deployment.md
- octoacme-retrospective-and-continuous-improvement.md
- octoacme-roles-and-personas.md

## Getting Started
- New to OctoAcme? Start with `octoacme-project-management-overview.md`
- Starting a new project? Follow `octoacme-project-initiation.md`
- In active delivery? Reference `octoacme-execution-and-tracking.md`

## Questions
If something is unclear, raise an issue or contact the Project Lead.
