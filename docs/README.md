# OctoAcme Project Management Documentation

**Purpose:** This documentation provides a comprehensive guide to OctoAcme's project management processes, helping teams deliver customer-focused projects efficiently and consistently.

## Overview

OctoAcme's project management approach emphasizes customer-first principles, iterative delivery, and clear ownership. Our processes span the entire project lifecycle—from initial problem validation through planning, execution, release, and retrospective—with the goal of maximizing customer value while maintaining transparency and psychological safety across teams.

At the core of our approach are clearly defined roles: **Project Managers (PMs)** coordinate delivery, schedules, and risk; **Product Managers (PdMs)** define outcomes and prioritize the backlog; **Developers** build and test features; and **QA/Testing** ensures quality standards are met. Each project also engages stakeholders who provide critical input and approvals. Communication is structured around a regular cadence: weekly PM-PdM syncs, twice-weekly team standups, and monthly stakeholder updates, with escalation paths for blockers and risks.

Quality assurance and risk management are embedded throughout execution. Teams use Definition of Done (DoD) criteria, automated CI testing, security scanning, and a living risk register updated weekly. Projects maintain key artifacts—such as the project one-pager, backlog, DoD, risk register, release notes, and retrospective action items—in the project repository to ensure a single source of truth. This integrated approach helps OctoAcme teams ship reliable increments, learn continuously, and adapt quickly based on evidence and feedback.

Retrospectives and continuous improvement complete the cycle, converting learnings into actionable next steps that feed back into planning and execution. By following these lightweight, adaptable processes, OctoAcme teams maintain alignment, reduce unplanned work, and consistently deliver measurable impact.

## Project Lifecycle

OctoAcme projects follow a structured lifecycle to ensure clarity and alignment:

1. **Initiation** — Validate the problem, identify stakeholders, and create a project one-pager with success metrics
2. **Planning** — Break work into a prioritized backlog, define Definition of Done, and map dependencies and milestones
3. **Execution** — Build, test, and iterate using daily standups, PR workflows, and continuous QA
4. **Release** — Deploy to production with release notes, smoke tests, and stakeholder communication
5. **Retrospective** — Capture learnings and action items to continuously improve team practices

### Key Artifacts

- **Project One-pager**: Problem statement, goals, success metrics, and timeline
- **Backlog**: Prioritized list of features and tasks with acceptance criteria
- **Definition of Done (DoD)**: Quality standards each work item must meet
- **Risk Register**: Tracked risks with impact, likelihood, owner, and mitigation plans
- **Release Notes**: Summary of changes, known issues, and migration steps
- **Retrospective Notes**: What went well, what to improve, and actionable next steps

## Process Documentation

Explore detailed guidance for each phase of the project lifecycle:

- [**Project Management Overview**](./octoacme-project-management-overview.md) — Core principles, roles, artifacts, and communication cadence
- [**Roles and Personas**](./octoacme-roles-and-personas.md) — Responsibilities and goals for Developers, Product Managers, and Project Managers
- [**Project Initiation**](./octoacme-project-initiation.md) — Validate ideas, create the one-pager, and decide to proceed
- [**Project Planning**](./octoacme-project-planning.md) — Build the backlog, estimate work, and define the release plan
- [**Execution and Tracking**](./octoacme-execution-and-tracking.md) — Day-to-day team rhythm, PR workflows, and quality practices
- [**Risk Management & Communication**](./octoacme-risks-and-communication.md) — Identify and mitigate risks, communicate with stakeholders
- [**Release and Deployment**](./octoacme-release-and-deployment.md) — Pre-release checks, deployment steps, and rollback procedures
- [**Retrospective and Continuous Improvement**](./octoacme-retrospective-and-continuous-improvement.md) — Capture learnings and track improvement action items

## How to Use These Docs

### Where to Keep Project Artifacts

- **Project repository (`docs/`)**: Store your project charter, one-pager, release notes, and other project-specific documentation in the `docs/` folder of your project repository.
- **Copilot context (`.copilot/`)**: If you want GitHub Copilot Spaces to use process-specific guidance or templates as context, add relevant docs to the `.copilot/` directory in your repository.

### Requesting Process Updates

Have suggestions or identified gaps in these process docs? Submit a request using our issue template:

[**Request a Process Doc Update**](../.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml)

This helps us continuously refine and improve our project management practices based on team feedback and evolving needs.

---

**Questions or feedback?** Reach out to your Project Manager or Product Lead for guidance on applying these processes to your project.
