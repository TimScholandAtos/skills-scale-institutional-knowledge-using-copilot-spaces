# OctoAcme — Cross-Role Responsibility Matrix (RACI)

## Purpose
Define clear accountability for key project activities using the RACI model:
- **R**esponsible: Does the work
- **A**ccountable: Ultimately answerable for completion
- **C**onsulted: Provides input before decisions/actions
- **I**nformed: Kept up-to-date on progress

## How to Use This Matrix
1. Reference this during project planning to clarify who does what
2. Use as a communication guide for when to involve specific roles
3. Adapt based on team size (roles may be combined in smaller teams)
4. Review and update if responsibilities shift during the project

---

## Project Initiation & Planning

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Create project charter | R/A | C | I | C | I | I | I | I | C |
| Define success metrics | C | R/A | I | C | C | I | I | I | I |
| Stakeholder identification | R | A | I | C | I | I | I | C | I |
| Requirements gathering | C | C | I | R/A | C | I | I | I | C |
| User research | I | C | I | C | R/A | I | I | I | I |
| Initial risk assessment | R/A | C | C | C | I | I | C | I | C |
| Scope definition | A | R | C | C | C | I | I | I | I |
| Resource planning | R/A | C | C | I | I | I | I | I | I |
| Create project backlog | R | A | C | C | C | I | I | I | I |

---

## Design & Development

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Architecture design | I | C | R/A | I | I | I | I | I | C |
| UX design & prototyping | I | C | C | I | R/A | I | I | I | I |
| Wireframe reviews | I | C | C | C | R/A | I | I | I | I |
| User story refinement | C | C | C | R/A | C | C | I | I | I |
| Acceptance criteria definition | I | C | C | R/A | C | C | I | I | I |
| Code implementation | I | I | R/A | I | C | I | I | I | C |
| Code reviews | I | I | R | I | I | I | I | I | C |
| Security code review | I | I | C | I | I | I | I | I | R/A |
| Unit testing | I | I | R/A | I | I | C | I | I | I |
| Integration testing | I | I | R | I | I | C/A | I | I | C |
| Usability testing | I | C | I | I | R/A | C | I | I | I |

---

## Testing & Quality Assurance

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Test plan creation | I | I | C | C | I | R/A | I | I | C |
| Functional testing | I | I | C | C | I | R/A | I | I | I |
| Acceptance testing | I | C | C | C | C | R/A | I | I | I |
| Performance testing | I | I | C | I | I | R/A | I | I | I |
| Security testing | I | I | C | I | I | C | I | I | R/A |
| Accessibility testing | I | C | C | I | C | R/A | I | I | I |
| Bug triage | C | C | C | I | I | R/A | I | I | I |
| Bug fixes | I | I | R/A | I | I | C | I | I | C |
| Regression testing | I | I | C | I | I | R/A | I | I | I |
| Test sign-off | I | C | I | I | I | A | R | I | C |

---

## Release & Deployment

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Release planning | C | C | C | I | I | C | R/A | C | I |
| Release notes creation | I | C | C | I | I | I | R/A | C | I |
| Deployment scheduling | C | I | C | I | I | I | R/A | C | I |
| Pre-deployment checklist | I | I | C | I | I | C | R/A | I | C |
| Security sign-off | I | I | I | I | I | I | C | I | R/A |
| Deployment execution | I | I | R | I | I | I | A | I | C |
| Post-deployment verification | I | I | R | I | I | C | A | C | C |
| Rollback decision | C | C | C | I | I | I | R/A | I | I |
| Support handoff | I | C | C | I | I | I | R | A | I |
| Stakeholder communication | R/A | C | I | I | I | I | C | I | I |

---

## Support & Maintenance

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Support channel setup | I | I | C | I | I | I | I | R/A | I |
| Incident triage | C | I | C | I | I | I | I | R/A | C |
| Bug investigation | I | I | R | I | I | C | I | C | C |
| Hotfix development | I | I | R/A | I | I | C | C | C | C |
| Hotfix deployment | I | I | C | I | I | I | R/A | C | C |
| User feedback collection | I | C | I | I | I | I | I | R/A | I |
| FAQ/KB documentation | I | I | C | I | I | I | I | R/A | I |
| Issue escalation | C | C | C | I | I | I | I | R/A | I |
| Security incident response | C | I | C | I | I | I | I | C | R/A |

---

## Monitoring & Continuous Improvement

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Metrics monitoring | C | R/A | C | I | C | I | I | C | I |
| User analytics review | I | R/A | I | C | C | I | I | C | I |
| Retrospective facilitation | R/A | C | C | C | C | C | C | C | C |
| Action item tracking | R/A | I | C | I | I | I | I | I | I |
| Process documentation | R/A | C | C | C | C | C | C | C | C |
| Lessons learned capture | R/A | C | C | C | C | C | C | C | C |
| Security audit follow-up | C | I | C | I | I | I | I | I | R/A |

---

## Communication & Reporting

| Activity | PM | PdM | Dev | BA | UX | QA | Rel Mgr | Support | Security |
|----------|----|----|-----|----|----|----|---------|---------|---------| 
| Daily standup facilitation | R/A | C | C | C | C | C | C | C | C |
| Sprint planning | R/A | C | C | C | C | C | I | I | I |
| Sprint review/demo | R | A | R | C | C | C | I | I | I |
| Stakeholder status updates | R/A | C | I | I | I | I | I | I | I |
| Risk register updates | R/A | C | C | I | I | I | C | C | C |
| Decision documentation | R/A | C | C | C | C | I | I | I | I |
| Team meeting notes | R/A | C | C | C | C | C | C | C | C |

---

## Notes on Role Adaptation

### Small Teams
In smaller teams, roles are often combined:
- PM + PdM: Single owner for product and project management
- BA + QA: Combined analyst and testing role
- Security Champion: Part-time responsibility for senior developer

### Large Teams
In larger teams, roles may be further specialized:
- Multiple developers with tech leads
- Separate QA Automation and Manual QA roles
- Dedicated Release Engineering team
- Multiple Business Analysts per domain

### Adjusting the Matrix
- Modify based on your team's specific needs and structure
- Document any deviations in your project charter
- Review during retrospectives to ensure clarity and effectiveness

---

## Related Documents
- [Roles and Personas](octoacme-roles-and-personas.md) - Detailed role descriptions
- [Role Onboarding Guide](octoacme-role-onboarding-guide.md) - Getting started in each role
- [Milestone Collaboration Checklist](octoacme-milestone-checklist.md) - Phase-specific activities
- [Project Management Overview](octoacme-project-management-overview.md) - Overall process
