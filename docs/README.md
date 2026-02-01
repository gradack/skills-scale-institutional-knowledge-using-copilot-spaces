# OctoAcme Project Management Docs

Welcome to the OctoAcme Project Management documentation! This resource serves as the central hub for understanding how we plan, execute, and deliver projects at OctoAcme. Whether you're a new team member looking to get up to speed, or an experienced contributor seeking guidance on a specific process, you'll find comprehensive information here to help you succeed.

## Summary of Project Management Processes

### Process Overview

OctoAcme follows an iterative, milestone-driven delivery model grounded in five core principles:

- **Customer-first prioritization**: We prioritize customer value and usability in all decision-making
- **Iterative delivery**: We deliver small, testable increments that provide continuous value
- **Clear ownership**: Every project has named Project Managers and Product Leads with defined responsibilities
- **Data-informed decision-making**: We base decisions on measurable evidence and track meaningful metrics
- **Psychological safety**: We encourage feedback and learning, creating an environment where team members can speak up

The project lifecycle consists of five distinct phases:

1. **Initiation**: Define the problem statement, stakeholders, and high-level timeline
2. **Planning**: Establish scope, resources, milestones, and dependencies
3. **Execution**: Build, test, review, and iterate on solutions
4. **Release**: Deploy, verify, and announce the completed work
5. **Retrospective**: Capture learnings and identify action items for continuous improvement

Projects begin with a lightweight **Project One-pager** that defines:
- Problem statement and context
- SMART objectives (Specific, Measurable, Achievable, Relevant, Time-bound)
- Success metrics and KPIs
- Key stakeholders and their roles
- Suggested timeline and major milestones
- Initial risks and dependencies
- Proposed team roles and responsibilities

### Team Structure

**Project Managers** are responsible for:
- Coordinating delivery activities across the team
- Managing schedules, timelines, and milestone tracking
- Maintaining the risk register and escalating issues
- Facilitating meetings (standups, planning, retrospectives)
- Ensuring consistent documentation and artifact updates
- Maintaining transparency across stakeholders

**Product Managers** are responsible for:
- Owning the product vision and strategy
- Prioritizing the roadmap and backlog
- Defining problem statements and success metrics
- Validating solutions through user research and metrics analysis
- Making trade-off decisions on scope and priorities

**Developers** are responsible for:
- Implementing features that meet acceptance criteria
- Writing and maintaining tests and technical documentation
- Participating in design and code reviews
- Assisting in estimating and planning work
- Collaborating with QA to ensure quality standards

**QA/Testing** professionals are responsible for:
- Validating that quality standards are met
- Ensuring acceptance criteria are satisfied
- Executing test plans and reporting defects
- Contributing to test automation strategies

### Day-to-Day Execution

**Daily Operations:**
- **Daily standups**: 15-minute focused meetings covering progress, blockers, and dependencies
- **Weekly delivery syncs**: Show progress, demo completed work, and flag risks
- **Sprint/milestone reviews**: Demos or reviews at the end of each sprint or milestone to gather feedback

**Project Boards** (GitHub Projects):
- Workflow columns: Backlog → Ready → In Progress → In Review → QA → Done
- All work items tracked with clear owners and acceptance criteria
- Regular grooming to keep backlog prioritized and refined

**Pull Request Workflow:**
- Small PRs (≤400 lines when possible) for easier review and faster integration
- Automated testing in CI to catch issues early
- At least one approval required before merging
- Clear descriptions linking to issues and explaining changes

**Multi-layered Quality Assurance:**
- **Unit tests**: Test individual components and functions
- **Integration tests**: Validate interactions between components
- **End-to-end smoke tests**: Verify critical user flows work correctly
- **Security scanning**: Automated checks for vulnerabilities and compliance

### Communication & Continuous Improvement

**Risk Register Tracking:**
Each risk is documented with:
- Unique ID for tracking
- Clear description of the risk
- Impact assessment (High/Medium/Low)
- Likelihood assessment (High/Medium/Low)
- Owner responsible for monitoring and mitigation
- Mitigation plan with specific actions
- Current status (Open/Monitoring/Mitigated/Closed)

**Communication Cadence:**
- **Weekly PM-Product Lead syncs**: Align on priorities, address blockers, review risks
- **Twice-weekly team standups**: Share progress, identify dependencies
- **Monthly stakeholder updates**: Share progress, upcoming milestones, and key decisions

**Release Management:**
- Standardized pre-release requirements and deployment checklists
- Clear rollback procedures and monitoring plans
- Communication plans for user-facing changes
- Post-deployment verification and smoke testing

**Retrospectives:**
- Timeboxed sessions (45-75 minutes) after each sprint, release, or milestone
- Structured format: What went well, what could be improved, action items
- Action items tracked in backlog with clear owners and due dates
- Review of previous action items in weekly syncs to ensure accountability

## Process Docs Index

The following process documents provide detailed guidance for each aspect of project management at OctoAcme:

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)

## Getting Started

For detailed information on any specific topic, please refer to the linked process documents above. Each document provides in-depth guidance, templates, and examples to help you successfully execute that aspect of project management.

If you're new to OctoAcme, we recommend starting with the [Project Management Overview](octoacme-project-management-overview.md) to understand our high-level approach, then diving into specific process documents as needed for your role and current project phase.
