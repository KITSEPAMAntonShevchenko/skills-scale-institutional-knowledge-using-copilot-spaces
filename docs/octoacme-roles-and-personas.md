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

### Key Interactions
- **With QA/Testing Lead**: Collaborate on testability requirements and acceptance criteria validation
- **With Technical Lead/Architect**: Receive technical guidance and architecture decisions
- **With Project Manager**: Participate in planning and status updates

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

### Key Interactions
- **With Project Manager**: Align on priorities, timelines, and resource allocation
- **With Stakeholder/Sponsor**: Communicate business value and gather approval for roadmap
- **With QA/Testing Lead**: Define acceptance criteria and quality expectations

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

### Key Interactions
- **With Technical Lead/Architect**: Escalate technical risks and feasibility concerns
- **With Release Manager**: Coordinate deployment windows and release schedules
- **With Stakeholder/Sponsor**: Provide executive visibility and escalate blockers

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy and test execution. They collaborate with Developers on testability requirements, validate acceptance criteria, and ensure quality standards are met before release.

### Responsibilities
- Define QA approach and test strategy for projects
- Create and maintain comprehensive test plans
- Coordinate acceptance testing and quality validation
- Identify quality risks and propose mitigations
- Establish quality metrics and track test coverage
- Review test automation approach and manage test infrastructure

### Goals
- Ensure product quality and reliability
- Reduce defects reaching production
- Enable fast, confident releases through quality validation
- Maintain high test coverage and observability

### Typical Communication
- Quality reviews during sprint planning and retrospectives
- Test plan reviews and acceptance criteria walkthroughs
- Quality status reports and defect escalation
- Collaboration with Developers on testing approach

### Key Interactions
- **With Developers**: Partner on testability, review acceptance criteria, validate solutions against requirements
- **With Product Manager**: Collaborate on acceptance criteria clarity and quality expectations
- **With Project Manager**: Report quality status and escalate quality blockers
- **With QA/Compliance Officer**: Coordinate security and compliance testing requirements

---

## Technical Lead/Architect

### Role Summary
Technical Leads/Architects provide technical direction and manage technical risks. They review architecture and design decisions, guide technical debt management, and ensure solutions are technically sound and scalable.

### Responsibilities
- Advise on technical feasibility of features and initiatives
- Review and approve technical architecture and design
- Identify technical and integration risks early
- Guide technical debt decisions and mitigation strategies
- Mentor Developers on technical best practices
- Evaluate and recommend technology choices and tools

### Goals
- Ensure solutions are technically sound, scalable, and maintainable
- Reduce technical risk and rework
- Build team technical capability and knowledge
- Enable effective communication between technical and non-technical stakeholders

### Typical Communication
- Technical design reviews and architecture decisions
- Risk assessment and mitigation planning
- Technical mentorship in code reviews and design discussions
- Integration planning and dependency coordination

### Key Interactions
- **With Developers**: Mentor and review technical designs, escalate technical blockers
- **With Project Manager**: Identify technical risks and advise on feasibility and timeline impact
- **With QA/Testing Lead**: Define testability requirements and test strategy
- **With Release Manager**: Advise on rollback procedures and technical deployment considerations

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders/Sponsors provide business context, strategic alignment, and removal of organizational blockers. They approve project charters, make go/no-go decisions, and ensure projects deliver business value.

### Responsibilities
- Provide business context and strategic alignment for projects
- Approve project charters and major milestone decisions
- Make go/no-go decisions on project continuation
- Remove organizational blockers and resource constraints
- Sign off on releases and major deliverables
- Communicate project status to broader organizational leadership

### Goals
- Ensure projects deliver measurable business value
- Maintain strategic alignment across initiatives
- Enable smooth delivery by removing blockers
- Build confidence in project outcomes and team capability

### Typical Communication
- Project charter review and approval
- Milestone and release sign-off meetings
- Executive status briefings and decisions
- Escalation and blocker resolution

### Key Interactions
- **With Project Manager**: Receive regular status updates, make decisions, approve milestones
- **With Product Manager**: Align on business value and prioritization decisions
- **With Release Manager**: Sign off on releases and communicate to broader organization

---

## QA/Compliance Officer

### Role Summary
QA/Compliance Officers ensure regulatory, security, and compliance requirements are met. They review security controls, manage compliance risk, and audit release readiness to ensure products meet all necessary standards and regulations.

### Responsibilities
- Define and communicate compliance requirements for projects
- Review and validate security controls and implementation
- Maintain and monitor compliance risk register
- Conduct security and compliance audits of code and releases
- Coordinate security incident response and post-incident reviews
- Advise on risk mitigation strategies for security and compliance gaps
- Review PRs and releases with security focus

### Goals
- Ensure products meet all regulatory and compliance requirements
- Protect against security vulnerabilities and data breaches
- Build security and compliance awareness across teams
- Enable confident, compliant releases and deployments

### Typical Communication
- Security and compliance reviews in planning and release processes
- Risk assessment and mitigation planning
- Incident response coordination and escalation
- Compliance audit reports and corrective action tracking

### Key Interactions
- **With Developers**: Review code for security vulnerabilities, advise on secure coding practices
- **With Project Manager**: Escalate security and compliance risks, track risk mitigation
- **With QA/Testing Lead**: Coordinate security and compliance testing requirements
- **With Release Manager**: Audit releases for compliance readiness before deployment

---

## Release Manager

### Role Summary
Release Managers coordinate and execute release activities. They manage deployment windows, release documentation, rollback procedures, and post-deployment verification to ensure smooth, reliable releases.

### Responsibilities
- Coordinate and schedule deployment windows
- Prepare and maintain release notes and deployment documentation
- Execute deployment procedures and manage release rollout
- Manage rollback procedures in case of deployment failures
- Conduct post-deployment verification and monitoring
- Communicate release status to stakeholders and support teams
- Manage release checklist and pre-release validation

### Goals
- Execute releases smoothly and reliably
- Minimize deployment risk and customer impact
- Enable rapid incident response if issues occur
- Maintain clear communication with stakeholders during releases

### Typical Communication
- Release coordination meetings and deployment windows
- Release notes and deployment documentation
- Post-deployment status updates and incident communication
- Collaboration with DevOps and infrastructure teams

### Key Interactions
- **With Project Manager**: Coordinate release timing and dependencies
- **With Technical Lead/Architect**: Understand technical deployment considerations and rollback procedures
- **With QA/Compliance Officer**: Verify compliance readiness before deployment
- **With Stakeholder/Sponsor**: Communicate release status and get final approval

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Key Interactions section to understand cross-functional dependencies and communication patterns.
