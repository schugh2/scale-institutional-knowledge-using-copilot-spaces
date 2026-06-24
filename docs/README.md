# OctoAcme Project Management Process Documentation

## Overview

OctoAcme follows a structured, customer-first approach to project management that emphasizes iterative delivery, clear ownership, and data-informed decisions. Our processes are designed to reduce friction for teams, improve discoverability of best practices, and establish a single source of truth for project management knowledge.

### What is OctoAcme?

OctoAcme is a comprehensive project management framework that guides teams through the complete lifecycle of delivering features, services, and integrations. It provides standardized processes, clear role definitions, and proven communication strategies to ensure consistent, repeatable project execution across all teams.

## Core Principles

- **Customer-first**: Prioritize customer value and usability in all decisions
- **Iterative delivery**: Deliver small, testable increments to gather feedback early
- **Clear ownership**: Each project has a named Project Manager and Product Lead
- **Data-informed decisions**: Measure impact and iterate based on evidence
- **Psychological safety**: Encourage feedback, learning, and continuous improvement

## Process Lifecycle

OctoAcme projects follow a five-phase lifecycle:

1. **Initiation**: Define problem statement, identify stakeholders, establish high-level timeline, and secure sponsor approval
2. **Planning**: Break work into actionable increments, identify dependencies and risks, define acceptance criteria and Definition of Done
3. **Execution**: Build, test, review, and iterate with regular team rhythm (daily standups, weekly syncs, demos)
4. **Release**: Deploy to production with pre-release validation, smoke tests, and rollback planning
5. **Retrospective**: Capture learnings and convert them into actionable improvements

## Key Workflows & Practices

### Team Rhythm
- **Daily standups** (15 min): Focus on progress, blockers, and dependencies
- **Weekly delivery sync**: Show progress, updates, and flagged risks
- **Demo/Review**: At the end of each sprint or milestone
- **Monthly stakeholder updates**: Keep sponsors and stakeholders informed

### Execution Approach
- Use GitHub Projects with standardized columns: Backlog, Ready, In Progress, In Review, QA, Done
- Small pull requests (≤400 lines when possible) with issue links and acceptance criteria
- Automated CI/CD for tests, linting, and security scanning before requesting review
- At least one approval required before merging

### Quality & Testing
- Unit tests for new logic
- Integration tests where applicable
- End-to-end smoke tests for critical flows before release
- Security scanning in CI
- Manual QA for feature acceptance when needed

### Risk Management
- Maintain a Risk Register with ID, Description, Impact, Likelihood, Owner, and Mitigation Plan
- Escalation path: Team-level → PM → Product Lead → Sponsor
- Review and update risks at weekly syncs

## Team Roles & Responsibilities

OctoAcme operates with clearly defined cross-functional roles:

- **Project Managers**: Coordinate delivery, manage schedules, risks, and communications
- **Product Managers**: Define outcomes, prioritize backlog, measure success, and validate solutions
- **Developers**: Implement features, write tests, conduct code reviews, and help identify technical risks
- **QA/Testing**: Validate quality, test acceptance criteria, and ensure fitness for release

See [Roles & Personas](octoacme-roles-and-personas.md) for detailed responsibilities for each role.

## Documentation

### Getting Started
- **[Project Management Overview](octoacme-project-management-overview.md)** — Start here for roles, artifacts, and high-level lifecycle
- **[Roles & Personas](octoacme-roles-and-personas.md)** — Understand team roles and typical responsibilities

### Process Guides (in order)
- **[Project Initiation](octoacme-project-initiation.md)** — Validate business need and align stakeholders
  - One-pager template, stakeholder identification, decision gate
- **[Project Planning](octoacme-project-planning.md)** — Turn initiatives into actionable backlogs
  - Backlog creation, estimation, dependencies, release planning
- **[Execution & Tracking](octoacme-execution-and-tracking.md)** — Manage day-to-day delivery and progress
  - Team rhythm, project board workflow, quality standards, blocker escalation
- **[Risk Management & Communication](octoacme-risks-and-communication.md)** — Identify and manage risks
  - Risk Register, stakeholder communication, escalation paths
- **[Release & Deployment](octoacme-release-and-deployment.md)** — Standardize how we release to production
  - Release types, pre-release requirements, deployment checklist, rollback playbook
- **[Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)** — Capture learnings
  - Retrospective structure, action item tracking, measuring impact

## Quick Reference Guide

### Common Questions
- **How do I start a new project?** → [Project Initiation Guide](octoacme-project-initiation.md)
- **How do I plan delivery?** → [Project Planning](octoacme-project-planning.md)
- **What's expected in daily execution?** → [Execution & Tracking](octoacme-execution-and-tracking.md)
- **How do I manage risks?** → [Risk Management & Communication](octoacme-risks-and-communication.md)
- **How do I release safely?** → [Release & Deployment Guide](octoacme-release-and-deployment.md)
- **What are my responsibilities?** → [Roles & Personas](octoacme-roles-and-personas.md)
- **How do we improve from lessons learned?** → [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Using These Docs in Your Project

1. **During Project Initiation**: Reference the [Project Initiation](octoacme-project-initiation.md) guide and create a Project One-pager
2. **During Planning**: Use the backlog template and checklists from [Project Planning](octoacme-project-planning.md)
3. **During Execution**: Keep the team rhythm and execution checklist from [Execution & Tracking](octoacme-execution-and-tracking.md) visible
4. **For Cross-team Work**: Reference [Risk Management & Communication](octoacme-risks-and-communication.md) for dependencies and escalation
5. **Before Release**: Complete the deployment checklist in [Release & Deployment](octoacme-release-and-deployment.md)
6. **After Completion**: Run a retrospective using the structure in [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)

## Adding to Copilot Spaces

To use these process documents as context in a Copilot Space:
1. Add individual process docs to your `.copilot/` folder or reference this README
2. Reference specific guides in your Space's context to provide role-specific or phase-specific guidance
3. Use the issue template `.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml` to propose updates or new content

## Feedback & Continuous Improvement

Have suggestions for improving these processes? Use the [Process Doc Update issue template](.github/ISSUE_TEMPLATE/add-update-content-to-process-docs.yml) to propose changes, additions, or clarifications.

---

**Last Updated**: June 2026  
**Maintainer**: OctoAcme Team
