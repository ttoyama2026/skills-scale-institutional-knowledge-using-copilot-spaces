# OctoAcme Project Management Docs

This repository contains OctoAcme's project management process documentation. The files in docs/ describe how we initiate, plan, execute, release, and continuously improve projects, and provide templates and checklists to keep work discoverable and consistent.

OctoAcme follows a lightweight lifecycle: Initiation (a Project One-pager that states the problem, goals, success metrics, stakeholders, and initial risks), Planning (turning the approved initiative into a prioritized backlog with acceptance criteria, estimates, and a release plan), Execution (iterative development with clear DoD, small PRs, CI checks, and regular demos), Release (standardized deployment checklists, smoke tests, and rollback plans), and Close & Retrospective (blameless reviews and tracked action items). The approach emphasizes customer-first outcomes, iterative delivery, clear ownership, data-informed decisions, and psychological safety.

Roles and communication are explicit: Product Managers define outcomes and prioritize the backlog, Project Managers coordinate schedules, risks, and stakeholder updates, Developers implement and test, and QA validates acceptance criteria. Team rhythm includes regular standups and weekly PM/PdM syncs, sprint demos/reviews, and monthly stakeholder updates. Risks and dependencies are tracked in a risk register and escalated through defined paths when needed.

Quality is a shared responsibility: acceptance criteria and a Definition of Done are required for backlog items; pull requests should be small, include issue links and acceptance criteria, and pass automated tests, linting, and security scans before review. Releases require pre-release checks, smoke tests, and post-deploy verification; incidents follow an incident communication template and a blameless retrospective process.

## Documents

- [Project Management Overview](./octoacme-project-management-overview.md)
- [Project Initiation Guide](./octoacme-project-initiation.md)
- [Project Planning](./octoacme-project-planning.md)
- [Execution & Tracking](./octoacme-execution-and-tracking.md)
- [Release & Deployment Guide](./octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md)
- [Risk Management & Communication](./octoacme-risks-and-communication.md)
- [Roles & Personas](./octoacme-roles-and-personas.md)

---

To propose changes or add new process content, open a new issue using the "Add Content to Project Management Process Docs" template and select "<new document>" if creating a new doc. Keep docs in docs/ and follow the repository's documentation and PR conventions.
