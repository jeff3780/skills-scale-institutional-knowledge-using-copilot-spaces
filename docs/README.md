# OctoAcme Project Management Process Documentation

## Purpose
This documentation provides a comprehensive guide to OctoAcme's project management processes, enabling teams to deliver customer-focused, high-quality projects efficiently. These docs serve as the single source of truth for how we plan, execute, and continuously improve our delivery practices.

## Overview

OctoAcme follows a structured, iterative approach to project management that prioritizes customer value, clear ownership, and data-informed decisions. Our processes are designed to maintain psychological safety while ensuring accountability and transparency across all project phases.

Our project lifecycle moves through five core phases: **Initiation → Planning → Execution → Release → Retrospective**. Each phase has defined goals, key artifacts, and decision gates to ensure alignment and quality. Projects begin with a lightweight one-pager that defines the problem, success metrics, and stakeholders. During planning, we break work into a prioritized backlog with clear acceptance criteria and a Definition of Done (DoD). Throughout execution, teams use daily standups, weekly syncs, and continuous testing to track progress and manage risks via a risk register. Releases follow standardized deployment checklists and include comprehensive release notes. Finally, retrospectives capture learnings and convert them into actionable improvements.

Key roles drive this process: Project Managers coordinate delivery, schedules, and communications; Product Managers define outcomes and prioritize the backlog; Developers implement features with quality and testability in mind; and QA validates acceptance criteria. Communication happens through weekly PM-PdM syncs, twice-weekly standups, monthly stakeholder updates, and ad-hoc escalations. Quality assurance is built in through automated testing, code reviews, security scans, and manual QA as needed.

Our approach emphasizes small, testable increments delivered iteratively, with each project maintaining key artifacts including the project one-pager, backlog, Definition of Done, risk register, release notes, and retrospective action items. These artifacts ensure teams can quickly onboard, understand project status, and maintain continuity throughout the delivery lifecycle.

## Process Documentation

- [**octoacme-project-management-overview.md**](./octoacme-project-management-overview.md) — High-level introduction to OctoAcme's approach, core principles, roles, and lifecycle
- [**octoacme-project-initiation.md**](./octoacme-project-initiation.md) — How to validate ideas, create a project one-pager, and get approval to proceed
- [**octoacme-project-planning.md**](./octoacme-project-planning.md) — Breaking work into shippable increments, defining DoD, and creating release plans
- [**octoacme-execution-and-tracking.md**](./octoacme-execution-and-tracking.md) — Day-to-day workflows, quality practices, and progress tracking
- [**octoacme-risks-and-communication.md**](./octoacme-risks-and-communication.md) — Risk management, stakeholder communication, and escalation paths
- [**octoacme-release-and-deployment.md**](./octoacme-release-and-deployment.md) — Release types, deployment checklists, and rollback procedures
- [**octoacme-retrospective-and-continuous-improvement.md**](./octoacme-retrospective-and-continuous-improvement.md) — Capturing learnings and driving actionable improvements
- [**octoacme-roles-and-personas.md**](./octoacme-roles-and-personas.md) — Detailed role definitions and responsibilities for developers, product managers, and project managers

## How to Use These Docs

### Storing Project Artifacts
- Keep your **Project Charter, one-pager, and key status docs** in your project repository's `docs/` folder for team visibility
- Add **process-specific guidance or templates** to `.copilot/` if you want GitHub Copilot Spaces to use them as context for code and project assistance
- Maintain a **single source of truth** for project status — typically the project README or a pinned release doc

### Requesting Process Updates
Have suggestions for improving these process docs? We welcome contributions!

To request updates or additions to any process document:
1. Open an issue using the [**Add Content to Project Management Process Docs**](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) template
2. Describe the content you'd like to add and why it's needed
3. Include any proposed text or examples
4. The process owner will review and incorporate valuable feedback

These docs are living documents that evolve based on team learnings and feedback. Your input helps us continuously improve our delivery practices.
