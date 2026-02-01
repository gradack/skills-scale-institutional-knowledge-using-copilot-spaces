# RACI Matrix Template

## Purpose
A RACI matrix clarifies accountability by defining who is Responsible, Accountable, Consulted, and Informed for each project activity. Use this template to establish clear ownership and avoid confusion about roles and responsibilities.

## RACI Definitions

- **Responsible (R)**: Person(s) who do the work to complete the task. There can be multiple responsible parties.
- **Accountable (A)**: Person who is ultimately answerable for the correct completion of the task. There must be exactly ONE accountable person per activity.
  - *Note: When the accountable person is also doing the work, both A and R can be assigned to the same person (shown as A/R).*
- **Consulted (C)**: People who provide input and expertise before decisions are made. Two-way communication.
- **Informed (I)**: People who are kept up-to-date on progress. One-way communication.

## How to Use This Template

1. List project activities or deliverables in the left column
2. Add relevant roles across the top row
3. Assign RACI designations for each activity/role intersection
4. Ensure each activity has exactly one Accountable (A) designation
5. Review with the team to confirm agreement on assignments

## RACI Matrix for OctoAcme Projects

| Activity / Deliverable | Project Sponsor | Project Manager | Product Manager | Business Analyst | Developer | QA Lead | Change Manager | Stakeholder |
|------------------------|-----------------|-----------------|-----------------|------------------|-----------|---------|----------------|-------------|
| **Initiation Phase** |
| Project charter approval | A | R | C | I | I | I | I | C |
| Problem statement definition | C | C | A/R | C | I | I | I | C |
| Stakeholder identification | C | R | C | C | I | I | I | I |
| Success metrics definition | C | C | A/R | C | I | I | I | C |
| Resource allocation | A | C | C | I | I | I | I | I |
| **Planning Phase** |
| Requirements gathering | I | C | C | A/R | C | C | I | C |
| Backlog prioritization | C | C | A/R | C | I | I | I | C |
| Sprint/milestone planning | I | A/R | C | C | R | C | I | I |
| Risk identification | I | A/R | C | C | R | C | I | C |
| Test strategy definition | I | C | C | I | C | A/R | I | I |
| **Execution Phase** |
| Feature implementation | I | C | C | C | A/R | C | I | I |
| Code reviews | I | I | I | I | A/R | C | I | I |
| Testing execution | I | C | I | I | C | A/R | I | I |
| Defect resolution | I | C | C | C | A/R | C | I | I |
| Change request evaluation | I | C | C | C | C | I | A/R | C |
| Status reporting | I | A/R | C | I | I | I | I | I |
| **Review & Release Phase** |
| Acceptance validation | I | C | C | C | C | A/R | I | C |
| Release approval | C | C | A | I | I | C | C | I |
| Deployment execution | I | A/R | C | I | R | C | I | I |
| Stakeholder communication | C | R | C | I | I | I | R | I |
| Go-live decision | A | C | C | I | I | C | C | C |
| **Retrospective Phase** |
| Retrospective facilitation | I | A/R | C | C | C | C | I | I |
| Action item tracking | I | A/R | C | I | I | I | I | I |
| Lessons learned documentation | I | A/R | C | C | C | C | I | I |

## Customization Guidelines

**Adapt this matrix for your specific project:**
- Add or remove roles based on your team composition
- Modify activities to match your project phases and deliverables
- Ensure every activity has exactly one Accountable party
- Review and update the matrix if roles or responsibilities change
- Share the completed matrix with all team members at project kickoff

## Best Practices

1. **Keep it simple**: Only include activities where accountability needs clarification
2. **Review regularly**: Update the matrix when the project scope or team changes
3. **Communicate clearly**: Share the RACI matrix during project kickoff and onboarding
4. **Resolve conflicts**: If multiple people claim to be Accountable, escalate to resolve
5. **Document exceptions**: Note any special circumstances or temporary assignments

## Example: Feature Implementation

For a specific feature like "User Authentication API":

| Activity | Sponsor | PM | PdM | BA | Dev | QA Lead | Change Mgr | Stakeholder |
|----------|---------|----|----|----|----|---------|------------|-------------|
| Define auth requirements | I | C | C | A/R | C | C | I | C |
| Design API specification | I | I | C | C | A/R | C | I | I |
| Implement auth service | I | I | C | I | A/R | C | I | I |
| Create test plan | I | C | I | I | C | A/R | I | I |
| Execute security testing | I | I | C | I | C | A/R | I | I |
| Approve for release | C | C | A | I | I | C | C | I |
| Deploy to production | I | A/R | C | I | R | C | C | I |

---

## Related Documentation
- [Roles & Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Project Management Overview](octoacme-project-management-overview.md) - Process overview
- [Risk Management & Communication](octoacme-risks-and-communication.md) - Escalation paths

---

_This template was created as part of issue [#4](https://github.com/gradack/skills-scale-institutional-knowledge-using-copilot-spaces/issues/4) to improve accountability clarity and role interfaces._
