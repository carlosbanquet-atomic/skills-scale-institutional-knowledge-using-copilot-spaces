# OctoAcme Project Management Docs

Welcome to the OctoAcme project management documentation suite. These guides define how the team plans, delivers, communicates, and improves work across project lifecycles. The documentation is designed to help new teammates and stakeholders quickly understand how OctoAcme manages work from idea to release.

OctoAcme uses a structured, iterative lifecycle that spans Initiation, Planning, Execution, Release, and Close & Retrospective. The approach is grounded in five guiding principles: customer-first value delivery, iterative execution, clear ownership, data-informed decisions, and psychological safety.

## Table of Contents

### Project Management Foundation
- [Project Management Overview](./octoacme-project-management-overview.md) — Core roles, principles, artifacts, and lifecycle
- [OctoAcme Personas](./octoacme-roles-and-personas.md) — Role summaries and communication patterns for common team members

### Phase 1: Initiation
- [Project Initiation Guide](./octoacme-project-initiation.md) — Validate the business need, align stakeholders, and decide whether to move forward

### Phase 2: Planning
- [Project Planning](./octoacme-project-planning.md) — Create the backlog, define acceptance criteria, estimate work, and map dependencies

### Phase 3: Execution & Tracking
- [Execution & Tracking](./octoacme-execution-and-tracking.md) — Run day-to-day delivery, track progress, and escalate blockers
- [Risk Management & Communication](./octoacme-risks-and-communication.md) — Manage risk, dependencies, and stakeholder updates

### Phase 4: Release & Deployment
- [Release & Deployment Guide](./octoacme-release-and-deployment.md) — Standardize pre-release checks, deployment steps, verification, and rollback playbooks

### Phase 5: Close & Continuous Improvement
- [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) — Capture learning, document action items, and reinforce improvement habits

## Lifecycle Summary

OctoAcme’s project lifecycle follows a clear progression:

1. Initiation: confirm the problem, define success metrics, and align stakeholders
2. Planning: break work into manageable increments and agree on milestones and ownership
3. Execution: build, test, review, and iterate with visible progress and transparent blockers
4. Release: validate quality, deploy with controls, and communicate outcomes
5. Close & Retrospective: document lessons learned and convert them into action

## Quick Reference by Scenario

| Scenario | Start Here | Key Artifacts |
| --- | --- | --- |
| New idea or initiative needs validation | [Project Initiation Guide](./octoacme-project-initiation.md) | One-pager, stakeholder list, risk list, initial timeline |
| Approved project needs a concrete delivery plan | [Project Planning](./octoacme-project-planning.md) | Backlog, acceptance criteria, milestones, DoD, release plan |
| Team is building and tracking progress | [Execution & Tracking](./octoacme-execution-and-tracking.md) | Project board, PR workflow, checklists, blocker escalation |
| Risk, dependency, or stakeholder communication issue arises | [Risk Management & Communication](./octoacme-risks-and-communication.md) | Risk register, communication plan, escalation paths |
| Release is ready for production | [Release & Deployment Guide](./octoacme-release-and-deployment.md) | Release notes, smoke test plan, rollback plan |
| Milestone or sprint is complete | [Retrospective & Continuous Improvement](./octoacme-retrospective-and-continuous-improvement.md) | Retrospective notes, improvement actions, follow-up owners |
| Need to understand role expectations | [OctoAcme Personas](./octoacme-roles-and-personas.md) | Role summaries and responsibilities |

## Core Project Management Principles

- Customer-first: prioritize customer and stakeholder value
- Iterative delivery: ship small, testable increments
- Clear ownership: assign named owners for delivery and decision-making
- Data-informed decisions: measure outcomes and review evidence before major changes
- Psychological safety: create space for feedback, retrospectives, and continuous learning

## Common Team Workflows

- Daily standups to surface progress, blockers, and dependencies
- Weekly delivery syncs to review risks, decisions, and milestones
- Demos or reviews at the end of a sprint or milestone
- Small, reviewable pull requests with issue links and acceptance criteria
- CI validation before merge, with at least one approval required for protected workflows

## Quality & Assurance Expectations

- Unit tests for new logic
- Integration tests as appropriate for critical flows
- E2E smoke tests for key business scenarios
- Security scans in CI
- Manual QA when needed for feature acceptance
- Definition of Done documented before work is considered complete

## Recommended Usage

Use this documentation set as the default reference for OctoAcme project work. Keep the project’s one-pager and related artifacts updated in the repo, and use the relevant guidance in this folder whenever you are planning, executing, or closing a project.

This README acts as the central entry point for the OctoAcme process knowledge base and should be the first place a teammate or stakeholder looks when seeking guidance on how work is managed across the project lifecycle.
