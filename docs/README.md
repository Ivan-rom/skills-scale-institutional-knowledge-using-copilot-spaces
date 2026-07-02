# OctoAcme Project Management Docs

Welcome to OctoAcme's project management knowledge base. This directory contains comprehensive guidance for running projects using the OctoAcme framework, helping teams deliver customer value through structured, iterative processes.

## Quick Start

New to OctoAcme? Start with the [Project Management Overview](octoacme-project-management-overview.md) to understand our core principles, roles, artifacts, and communication cadence. Then follow the framework phases in order as you plan and execute your project.

## OctoAcme Framework at a Glance

OctoAcme projects follow a five-phase lifecycle focused on customer value and iterative delivery:

1. **Initiation** - Validate the business need and align stakeholders
2. **Planning** - Break work into shippable increments and create a roadmap
3. **Execution** - Build, test, and deliver with clear tracking and communication
4. **Release** - Deploy to production with confidence and minimize risk
5. **Retrospective** - Capture learnings and drive continuous improvement

## OctoAcme Project Management Overview

OctoAcme operates on a structured lifecycle that moves projects through five distinct phases, each with clear deliverables and decision gates. The **Initiation phase** validates business need and stakeholder alignment by producing a lightweight Project One-pager documenting problem statements, SMART objectives, success metrics, and initial risks. Once approved, projects move into **Planning**, where the team breaks work into shippable increments, establishes prioritized backlogs with acceptance criteria, defines a Definition of Done, and maps dependencies and release milestones.

Execution and delivery are coordinated through regular rhythms and governance structures. Teams maintain daily standups (15 minutes), weekly delivery syncs, and sprint-based planning tied to the project board (Backlog → Ready → In Progress → In Review → QA → Done). Pull requests follow lightweight discipline—targeting ≤400 lines with issue links and acceptance criteria—backed by automated CI checks and peer review requirements. Quality is embedded throughout via unit and integration tests, end-to-end smoke tests, and security scanning before release.

OctoAcme defines clear roles to maintain accountability: **Project Managers** own schedules, risks, and communications; **Product Managers** define scope and measure outcomes; **Developers** implement features with quality and identify risks; **QA/Testing** validates acceptance criteria. This separation prevents silos while maintaining clear communication flows through weekly PM-PdM syncs, twice-weekly standups, monthly stakeholder updates, and structured escalation paths (team → PM → Product Lead → Sponsor).

Risk management and continuous improvement are woven throughout. Teams maintain Risk Registers updated at weekly syncs, proactively escalate cross-team dependencies, and run retrospectives after each sprint or release to capture learnings and commit to prioritized action items. This learning-oriented culture ensures processes improve iteratively, reducing single-person dependency and accelerating onboarding through documented, validated workflows.

## Process Documentation

### Core Framework
- **[Project Management Overview](octoacme-project-management-overview.md)** - Core principles, roles, artifacts, and communication cadence. Start here to understand the OctoAcme approach.

### Lifecycle Phases
- **[Project Initiation](octoacme-project-initiation.md)** - Validate ideas, align stakeholders, and get authorization to proceed. Includes Project One-pager template and decision gate criteria.
- **[Project Planning](octoacme-project-planning.md)** - Create backlogs, estimate scope, define milestones, and identify dependencies. Includes backlog item and sprint planning templates.
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** - Manage day-to-day delivery, quality, and progress tracking. Covers team rhythm, PR workflows, testing strategy, and metrics.
- **[Release & Deployment](octoacme-release-and-deployment.md)** - Standardize releases and reduce deployment risk. Includes release types, checklists, rollback procedures, and release notes template.
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** - Capture learnings and drive improvements. Covers retrospective structure, action item tracking, and improvement culture.

### Cross-Cutting Concerns
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** - Identify risks, manage dependencies, and communicate status. Includes Risk Register template, escalation paths, and communication templates.
- **[Roles & Personas](octoacme-roles-and-personas.md)** - Define team roles and responsibilities. Documents Developers, Product Managers, Project Managers, and their goals and communication patterns.

## How to Use This Documentation

### For New Team Members
1. Read the [Project Management Overview](octoacme-project-management-overview.md) first to understand principles and roles
2. Review the [Roles & Personas](octoacme-roles-and-personas.md) document to understand your role and responsibilities
3. As you start a project, follow the lifecycle phases in order (Initiation → Planning → Execution → Release → Retrospective)
4. Use templates and checklists as starting points for your specific project

### For Project Execution
- Each document is self-contained but references related processes
- Use templates and checklists as starting points for your projects
- Keep project artifacts (charters, plans, risk registers) updated in your project repository
- Maintain a Risk Register and update it weekly during syncs
- Share status updates using the provided communication templates

### For Copilot Spaces Integration
- Store process-specific context in `.copilot/` for Copilot Spaces to use as reference material
- Attach relevant process docs to your Copilot Space to get context-specific guidance
- Link back to these docs from your project repository README for team reference

## Key Templates & Artifacts

Across these docs, you'll find:
- **Project One-pager** (Initiation) - Single-page summary of problem, goal, metrics, and team
- **Backlog Item Template** (Planning) - Standard format for prioritized work with acceptance criteria
- **Definition of Done** (Planning) - Checklist for work completion standards
- **Risk Register** (Risk Management) - Table tracking risks, impact, likelihood, and mitigation
- **Weekly Status Template** (Communication) - Consistent format for stakeholder updates
- **Release Notes Template** (Release) - Standard format for announcing changes to stakeholders
- **Action Item Template** (Retrospectives) - Format for tracking improvements with owners and timelines

## Questions or Feedback?

If you have questions about these processes or want to propose improvements:
1. Check if an existing process doc addresses your question
2. Raise the topic in your team's weekly sync or retrospective
3. Use the [Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose additions or clarifications
4. Work with your Product Lead or PM to incorporate improvements
