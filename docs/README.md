# OctoAcme Project Management Overview

This repository holds process documentation for OctoAcme projects. The docs in this folder summarize the project lifecycle, roles, workflows, and quality practices used across OctoAcme initiatives.

Summary of project management processes:

OctoAcme follows a staged, iterative lifecycle: initiation (one-pager and stakeholder alignment), planning (backlog, estimates, release plan), execution (short iterations and PR-driven development), release (staging verification and production deployments), and retrospective/continuous improvement.

Key workflows include:
- Project board with columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small pull requests with linked issues, acceptance criteria, CI checks, and at least one approval prior to merge
- Backlog item template (title, description, acceptance criteria, priority, estimate, owner)

Roles and communication:
- Named Project Manager (PM) and Product Lead for each project
- Developers deliver code and tests; QA validates acceptance
- Daily standups for blockers, weekly delivery syncs, sprint demos, and monthly stakeholder updates

Quality practices:
- Unit and integration tests, smoke tests, CI linting and security scans, and manual QA when necessary
- Release checklist with rollback plan and post-deploy verification

