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

## QA/Testing Lead

### Role Summary
QA/Testing Leads own quality assurance and testing strategy for deliverables. They collaborate with developers and product teams to define acceptance criteria, execute test plans, and validate that features meet quality standards before release.

### Responsibilities
- Define test strategy and test plan for features and releases
- Create and maintain automated and manual test cases
- Execute acceptance testing and validate against acceptance criteria
- Identify and triage quality issues with clear reproduction steps
- Collaborate with developers on test-driven development practices
- Conduct smoke tests and regression testing pre-release

### Goals
- Ensure high-quality, production-ready deliverables
- Reduce defects reaching production
- Improve test coverage and automation

### Interactions with Existing Roles
- **Developers**: Partner on test-driven development, code review test coverage, and debugging failed tests
- **Product Managers**: Align on acceptance criteria, validate feature completeness, and define quality standards
- **Project Managers**: Report quality status, identify test blockers, and coordinate release readiness

### Typical Communication
- Sprint planning and backlog refinement (define test criteria)
- Daily standups (report blockers and test status)
- Quality reviews and test result reporting
- Release readiness verification

---

## Technical Lead / Architect

### Role Summary
Technical Leads/Architects define the technical vision and design for projects. They own architectural decisions, identify technical risks, mentor developers, and ensure solutions are scalable, secure, and maintainable.

### Responsibilities
- Design technical architecture and solution approach
- Conduct design reviews and provide technical guidance
- Identify and mitigate technical risks and dependencies
- Mentor developers on best practices and standards
- Own decisions on tech stack, libraries, and frameworks
- Lead technical spike investigations for complex problems

### Goals
- Deliver scalable, maintainable, and secure solutions
- Reduce technical debt and improve code quality
- Enable team growth through mentorship and knowledge sharing

### Interactions with Existing Roles
- **Developers**: Mentor on design patterns, conduct code reviews, and guide implementation decisions
- **Product Managers**: Advise on technical feasibility, trade-offs, and architectural implications of features
- **Project Managers**: Identify technical dependencies, estimate architectural work, and escalate technical risks

### Typical Communication
- Technical design reviews and architecture discussions
- Code reviews and design feedback
- Risk assessment and mitigation planning
- Tech talks and knowledge sharing sessions

---

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic alignment, and approval authority for projects. They ensure initiatives align with organizational goals and serve as escalation points for business-impacting decisions.

### Responsibilities
- Define business requirements and success criteria
- Provide budget, resource, and timeline approval
- Serve as escalation point for business-impacting decisions
- Communicate project value to leadership
- Review and approve major milestones and deliverables
- Manage cross-organizational dependencies and alignment

### Goals
- Ensure projects deliver business value aligned with strategy
- Minimize business risk and enable rapid decision-making
- Maintain stakeholder confidence and alignment

### Interactions with Existing Roles
- **Product Managers**: Align on roadmap priorities, approve business requirements, and validate success metrics
- **Project Managers**: Approve timelines and scope changes, escalate blockers, and receive status updates
- **Developers**: Review deliverables, provide business context, and approve go/no-go decisions

### Typical Communication
- Milestone reviews and approval gates
- Monthly stakeholder updates and steering committee meetings
- Executive summaries and business impact reporting
- Escalation and decision-making forums

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team processes, remove impediments, and coach teams on agile practices. They enable continuous improvement and help teams maintain velocity and psychological safety.

### Responsibilities
- Facilitate daily standups, planning, and retrospective ceremonies
- Identify and help remove blockers and impediments
- Coach team on agile principles and practices
- Maintain sprint board and track velocity metrics
- Foster psychological safety and continuous improvement culture
- Escalate organizational impediments to Project Manager

### Goals
- Enable consistent team delivery and predictable velocity
- Build high-performing, self-organizing teams
- Improve team morale and engagement

### Interactions with Existing Roles
- **Project Managers**: Coordinate ceremonies, escalate team-level blockers, and align on sprint planning
- **Developers**: Coach on sprint discipline, facilitate team discussions, and remove process blockers
- **All Roles**: Create safe space for feedback and foster continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- Retrospective facilitation and action item tracking
- Team health check-ins and 1-on-1 coaching
- Impediment logs and escalation reports

---

## Release Manager

### Role Summary
Release Managers coordinate all release activities, including planning, deployment scheduling, rollback procedures, and post-release verification. They ensure smooth transitions to production with minimal risk and clear communication.

### Responsibilities
- Plan and schedule release timelines and deployment windows
- Coordinate smoke tests and pre-release validation
- Execute or oversee deployment to staging and production
- Manage rollback procedures and incident response
- Prepare and distribute release notes
- Verify post-deployment health and metrics

### Goals
- Execute releases with high reliability and zero/minimal downtime
- Maintain clear communication with stakeholders during releases
- Enable rapid incident response and rollback if needed

### Interactions with Existing Roles
- **Developers**: Coordinate deployment activities, validate deployment readiness, and assist in incident response
- **QA/Testing Lead**: Conduct pre-release smoke tests, validate acceptance criteria, and verify release quality
- **Project Managers**: Communicate deployment status, manage release timeline, and escalate deployment risks
- **Stakeholders**: Provide release announcements, deployment schedules, and post-release communications

### Typical Communication
- Release planning meetings
- Deployment window coordination
- Release notes and stakeholder announcements
- Post-deployment verification and incident communication

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that projects meet security requirements, compliance standards, and organizational policies. They identify and mitigate security risks and help teams maintain a secure, compliant posture.

### Responsibilities
- Define security requirements and compliance standards for projects
- Conduct security reviews and threat assessments
- Manage security scanning and vulnerability remediation
- Ensure compliance with regulatory and organizational policies
- Provide security guidance and best practices training
- Escalate critical security risks and incidents

### Goals
- Prevent security breaches and compliance violations
- Build security-aware culture across the organization
- Maintain customer trust and regulatory compliance

### Interactions with Existing Roles
- **Developers**: Review code for security vulnerabilities, provide secure coding guidance, and support remediation
- **Technical Leads**: Advise on secure architecture patterns, threat modeling, and technology selection
- **Project Managers**: Identify security dependencies, estimate security work, and escalate critical risks
- **QA/Testing Lead**: Define security test cases, coordinate penetration testing, and validate security fixes

### Typical Communication
- Security reviews and threat assessments during design phase
- Vulnerability reports and remediation tracking
- Security incident response and post-incident reviews
- Compliance audits and regulatory communications

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
