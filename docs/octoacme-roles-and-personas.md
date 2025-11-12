# OctoAcme Personas

This document defines typical roles and responsibilities used in OctoAcme project docs and exercises.

---

## Developers

### Role Summary
Developers design, build, test, and deliver software components. They collaborate with product and project leads to implement features that meet acceptance criteria and quality standards.

### Responsibilities
- Implement features and fixes to meet acceptance criteria
- Write and maintain tests and documentation
- Participate in design and code reviews
- Assist in estimating and planning work
- Help identify technical risks and propose mitigations

### Goals
- Deliver reliable, maintainable code
- Reduce cycle time from idea to production
- Maintain high test coverage and observability

### Typical Communication
- Daily standups and sprint planning
- PR descriptions and code review comments
- Technical design docs when needed

---

## Product Managers

### Role Summary
Product Managers define what should be built to deliver customer and business value. They own the product vision, prioritize the backlog, and measure outcomes.

### Responsibilities
- Define problem statements and success metrics
- Prioritize the roadmap and backlog
- Collaborate with stakeholders and engineering on trade-offs
- Validate solutions through user research and metrics

### Goals
- Maximize customer value and impact
- Make clear, data-driven prioritization decisions
- Ensure product-market fit and usability

### Typical Communication
- Weekly alignment with PM and engineering leads
- Roadmap updates and stakeholder briefings
- Acceptance criteria and feature specs

---

## Project Managers

### Role Summary
Project Managers coordinate delivery activities, manage schedules, risks, and communications. They enable the team to deliver on commitments efficiently.

### Responsibilities
- Create and maintain project plans and timelines
- Manage risks, dependencies, and resource constraints
- Facilitate meetings (kickoff, planning, retrospectives)
- Ensure consistent project documentation and status reporting
- Coordinate cross-team and stakeholder communication

### Goals
- Deliver projects on time and within scope
- Minimize unplanned work and escalations
- Maintain transparency and alignment across stakeholders

### Typical Communication
- Weekly status updates and stakeholder reports
- Risk registers and decision logs
- Coordination via project boards and meeting facilitation

---

## Business Analysts

### Role Summary
Business Analysts bridge the gap between business stakeholders and technical teams. They elicit requirements, translate business needs into clear specifications, and ensure alignment throughout the project lifecycle.

### Responsibilities
- Lead discovery workshops and requirements gathering sessions
- Document use cases, user stories, and functional/non-functional requirements
- Validate scope and clarify acceptance criteria with Product and Project Managers
- Assist in backlog refinement and prioritization
- Analyze business processes and identify improvement opportunities
- Facilitate communication between stakeholders and development teams

### Goals
- Ensure requirements are clear, complete, and testable
- Minimize scope creep and requirement ambiguity
- Improve alignment between business needs and technical solutions
- Reduce rework through thorough upfront analysis

### Typical Communication
- Requirements workshops with stakeholders
- Backlog refinement sessions with Product Manager and Developers
- Acceptance criteria reviews with QA and Developers
- Business process documentation and user story mapping

### Key Interactions
- **With Product Managers:** Clarify vision and translate into detailed requirements
- **With Developers:** Explain business context and validate technical approaches
- **With Project Managers:** Define scope boundaries and track requirement changes
- **With Stakeholders:** Gather needs and validate proposed solutions

---

## UX Designers

### Role Summary
UX Designers create intuitive, accessible user experiences through research, design, and validation. They ensure products meet user needs and expectations while maintaining consistency and usability standards.

### Responsibilities
- Create wireframes, mockups, prototypes, and design specifications
- Conduct user interviews, usability testing, and user research
- Document design guidelines, patterns, and accessibility standards
- Validate designs with users and iterate based on feedback
- Review implementations to ensure design fidelity
- Maintain design system and component libraries

### Goals
- Deliver user-centered, accessible designs
- Reduce usability issues and improve user satisfaction
- Ensure design consistency across products
- Validate designs early through user testing

### Typical Communication
- Design reviews with Product Managers and Developers
- Usability testing sessions and user interviews
- Design critiques and feedback sessions
- Accessibility and design pattern documentation

### Key Interactions
- **With Product Managers:** Align on user needs and product vision
- **With Developers:** Collaborate on implementation feasibility and design specs
- **With Business Analysts:** Understand requirements and user workflows
- **With Project Managers:** Coordinate design milestones and deliverables

---

## Release Managers

### Role Summary
Release Managers coordinate and orchestrate deployment activities to ensure releases are well-planned, properly communicated, and successfully executed with minimal risk.

### Responsibilities
- Schedule and coordinate release activities across teams
- Prepare, review, and communicate release notes and documentation
- Orchestrate pre-release testing with QA and development teams
- Manage release calendars and deployment windows
- Ensure rollback and incident response plans are documented and ready
- Coordinate go-live communications with stakeholders and support teams

### Goals
- Execute smooth, reliable releases with minimal disruption
- Maintain clear release schedules and communication
- Minimize deployment risks through proper planning
- Ensure quick recovery through effective rollback procedures

### Typical Communication
- Release planning meetings with PM, Developers, and QA
- Deployment coordination and go-live status updates
- Release notes and communication to stakeholders
- Post-deployment retrospectives and incident reviews

### Key Interactions
- **With Developers:** Coordinate code freeze, deployment procedures, and technical requirements
- **With QA:** Ensure testing completion and sign-off before release
- **With Project Managers:** Align release schedules with project milestones
- **With Support Lead:** Hand off release information and prepare for user issues

---

## Support Leads

### Role Summary
Support Leads manage post-release user support, handle incidents and issues, and create feedback loops that inform product improvements and future planning.

### Responsibilities
- Set up and manage support channels (tickets, chat, email)
- Triage and track issue resolution and customer escalations
- Coordinate with Developers and QA on bug fixes and workarounds
- Document common issues, FAQs, and troubleshooting guides
- Share user feedback and pain points with Product and Engineering
- Track support metrics and identify trends for continuous improvement

### Goals
- Provide timely, effective support to users
- Minimize incident resolution time and user impact
- Feed user insights back into product development
- Build comprehensive knowledge base and support resources

### Typical Communication
- Daily triage meetings with Developers and QA
- Support ticket summaries and escalation reports
- Feedback sessions with Product Managers
- Knowledge base updates and user communications

### Key Interactions
- **With Release Manager:** Receive release handoffs and prepare support resources
- **With Developers:** Escalate bugs and coordinate on fixes
- **With Product Managers:** Share user feedback and feature requests
- **With QA:** Validate bug reproductions and test fixes

---

## Security Champions

### Role Summary
Security Champions embed security best practices throughout the development lifecycle, conduct security reviews, educate teams on threat mitigation, and ensure compliance with security standards.

### Responsibilities
- Review code and architecture for security vulnerabilities
- Conduct threat modeling and security risk assessments
- Educate teams on secure coding practices and OWASP guidelines
- Monitor security scanning results and coordinate remediation
- Ensure compliance with security policies and standards
- Act as liaison with central security team on incidents and audits

### Goals
- Prevent security vulnerabilities from reaching production
- Build security awareness and capability within teams
- Maintain compliance with security standards and regulations
- Respond quickly and effectively to security incidents

### Typical Communication
- Security review sessions during design and code review
- Security training and knowledge sharing with teams
- Threat assessment reports and vulnerability remediation plans
- Security incident coordination and post-mortems

### Key Interactions
- **With Developers:** Review code for security issues and provide secure coding guidance
- **With Architects:** Participate in design reviews and threat modeling
- **With Release Manager:** Verify security checks before deployment
- **With Project Managers:** Track security requirements and remediation timelines

---

## Cross-Role Collaboration

Effective project delivery requires clear coordination between roles. Below are key collaboration patterns:

### Planning & Initiation Phase
- **Project Manager** leads kickoff with all stakeholders
- **Business Analyst** facilitates requirements gathering workshops
- **Product Manager** defines vision and success metrics
- **UX Designer** conducts user research and creates initial concepts
- **Security Champion** reviews security requirements and constraints

### Execution Phase
- **Developers** implement features with input from BA and UX Designer
- **Business Analyst** clarifies requirements and validates acceptance criteria
- **UX Designer** reviews implementation for design fidelity
- **Security Champion** conducts code reviews and security scans
- **Project Manager** tracks progress and manages risks

### Testing & Quality Phase
- **QA** validates acceptance criteria defined by Business Analyst
- **UX Designer** conducts usability testing
- **Security Champion** reviews security test results
- **Release Manager** begins release preparation

### Release Phase
- **Release Manager** coordinates deployment activities
- **Developers** support deployment and monitor for issues
- **Support Lead** prepares support resources and monitors channels
- **Project Manager** communicates status to stakeholders

### Post-Release
- **Support Lead** triages user issues and escalates bugs
- **Developers** fix critical issues and plan improvements
- **Product Manager** analyzes metrics and user feedback
- **All roles** participate in retrospectives for continuous improvement

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the collaboration patterns when planning cross-functional activities.

