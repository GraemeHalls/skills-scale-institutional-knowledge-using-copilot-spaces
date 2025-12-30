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

## UX Designer

### Role Summary
UX Designers advocate for the user by ensuring usability and accessibility throughout product design and delivery. They collaborate with product and engineering teams to create intuitive, user-centered experiences.

### Responsibilities
- Lead user research and usability testing
- Create wireframes, prototypes, and design handoffs for implementation
- Collaborate with Product Managers and Developers on design solutions
- Ensure UI meets accessibility standards (WCAG compliance)
- Conduct design reviews and iterate based on user feedback
- Maintain design systems and component libraries

### Goals
- Deliver intuitive, accessible user experiences
- Validate design decisions through research and testing
- Reduce friction and improve user satisfaction scores
- Ensure consistent design language across products

### Typical Communication
- Design reviews with Product Manager and Developers
- Usability testing sessions with users
- Weekly sync on design deliverables and handoffs
- Accessibility audits and compliance reports

### Interactions with Other Roles
- **Product Managers**: Collaborate during requirements definition and feature prioritization
- **Developers**: Provide design specifications and feedback during implementation
- **QA/Testing**: Partner on usability testing and validation of acceptance criteria
- **Project Managers**: Coordinate on design milestones and dependencies

---

## Security Champion

### Role Summary
Security Champions embed security best practices into the project lifecycle. They identify risks, promote secure coding, and ensure the team maintains a security-first mindset throughout development.

### Responsibilities
- Identify and communicate security risks and vulnerabilities
- Promote secure coding practices and conduct code security reviews
- Oversee vulnerability remediation and security testing
- Conduct threat modeling for new features and systems
- Coordinate security reviews and incident response drills
- Stay current with security trends and emerging threats

### Goals
- Minimize security vulnerabilities and attack surface
- Build security awareness across the team
- Ensure compliance with security policies and standards
- Reduce time to detect and remediate security issues

### Typical Communication
- Security risk assessments in project planning
- Threat modeling sessions with architects and developers
- Security review feedback and remediation guidance
- Incident response coordination and postmortems

### Interactions with Other Roles
- **Developers**: Partner on secure coding practices and code reviews
- **Project Managers**: Coordinate on security risk management and mitigation plans
- **QA/Testing**: Collaborate on security testing and vulnerability validation
- **Product Managers**: Advise on security requirements and trade-offs

---

## Release Manager

### Role Summary
Release Managers coordinate and oversee the release process, ensuring readiness, compliance, and smooth deployments. They manage release schedules and communication to minimize risk and maximize reliability.

### Responsibilities
- Plan release schedules and coordinate with stakeholders
- Ensure pre-release checklists and readiness criteria are met
- Manage release communication and stakeholder notifications
- Oversee deployment execution and monitoring
- Coordinate rollback procedures when needed
- Maintain release documentation and postmortem reviews

### Goals
- Deliver reliable, low-risk releases on schedule
- Minimize deployment-related incidents and downtime
- Ensure clear communication throughout the release cycle
- Continuously improve release processes and automation

### Typical Communication
- Release planning meetings with Project Manager and engineering
- Pre-release go/no-go decision meetings
- Release status updates to stakeholders
- Post-release reviews and incident retrospectives

### Interactions with Other Roles
- **Project Managers**: Align on release schedules and risk management
- **Developers**: Coordinate on code freeze, testing, and deployment readiness
- **QA/Testing**: Ensure testing completion and sign-off before release
- **Automation Engineers**: Collaborate on deployment automation and monitoring
- **Product Managers**: Communicate release timelines and feature availability

---

## Automation Engineer

### Role Summary
Automation Engineers implement CI/CD pipelines, testing automation, and infrastructure automation to streamline delivery. They enable teams to deliver faster and more reliably through automated workflows.

### Responsibilities
- Create and maintain automation scripts for builds, tests, and deployments
- Monitor automation pipelines and address failures promptly
- Implement infrastructure as code and configuration management
- Optimize build and test performance
- Integrate security scanning and quality gates into pipelines
- Provide automation tools and training to the team

### Goals
- Maximize automation coverage for builds, tests, and deployments
- Reduce manual effort and human error in delivery processes
- Minimize build and deployment cycle time
- Ensure reliable, repeatable automation workflows

### Typical Communication
- Pipeline status reports and failure analysis
- Automation roadmap and improvement proposals
- Integration planning with development and QA teams
- Infrastructure and tooling documentation

### Interactions with Other Roles
- **Developers**: Collaborate on build requirements and test automation integration
- **QA/Testing**: Partner on test automation frameworks and execution
- **Release Managers**: Support deployment automation and monitoring
- **Project Managers**: Coordinate on automation priorities and timelines
- **Security Champions**: Integrate security scanning into CI/CD pipelines

---

## Communication Cadences and Decision Authority

### Regular Communication Patterns
- **Daily**: Standups involving Developers, QA, Automation Engineers (15 min focused on progress and blockers)
- **Weekly**: PM + Product Manager sync; Design reviews with UX Designer
- **Bi-weekly**: Sprint planning and retrospectives with full delivery team
- **Monthly**: Stakeholder updates; Security reviews with Security Champion
- **Per Release**: Release planning with Release Manager; Go/no-go decision meetings

### Decision-Making Authority During Critical Phases

#### Project Initiation
- **Product Manager**: Final authority on problem definition and success metrics
- **Project Manager**: Authority on timeline feasibility and resource allocation
- **Security Champion**: Authority on security requirements and risk acceptance

#### Planning Phase
- **Project Manager**: Authority on sprint scope and resource assignments
- **Product Manager**: Authority on feature prioritization and trade-offs
- **UX Designer**: Authority on design approach and usability standards

#### Execution Phase
- **Developers**: Authority on technical implementation approaches
- **QA/Testing**: Authority on quality gates and acceptance criteria validation
- **Security Champion**: Authority on security risk mitigation approaches

#### Release Phase
- **Release Manager**: Authority on go/no-go decisions and rollback procedures
- **Automation Engineer**: Authority on deployment automation and tooling
- **Product Manager**: Authority on feature flags and gradual rollout decisions

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Role definitions include clear responsibilities, communication patterns, and decision-making authority to support effective collaboration.
- KPIs and success metrics for each role can be defined during onboarding based on organizational goals.

