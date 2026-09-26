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

## Stakeholder / Sponsor

### Role Summary
Stakeholders and Sponsors provide business direction, funding, and executive visibility for projects. They prioritize organizational needs, define success criteria at a business level, and remove high-level blockers. Sponsors champion projects and ensure alignment with strategic objectives.

### Responsibilities
- Define business goals and success metrics for projects
- Approve project charter, timeline, and resource allocation
- Prioritize projects against competing organizational needs
- Provide executive sponsorship and escalation authority
- Review and approve major milestones and go/no-go decisions
- Communicate project status to broader leadership
- Remove organizational or policy-level blockers

### Goals
- Ensure projects deliver measurable business value
- Align project execution with organizational strategy
- Minimize project delays and resource conflicts
- Maximize ROI and stakeholder satisfaction

### Typical Communication
- Project initiation reviews and kick-off meetings
- Monthly or milestone-based executive status updates
- Escalation and blocker resolution
- Go/no-go decision gates
- Post-project reviews and business impact assessments

### Interactions with Other Roles
- **Product Manager**: Aligns on business priorities and success metrics
- **Project Manager**: Provides funding approval, timeline sign-off, and escalation authority
- **Developers/Tech Lead**: Reviews high-level technical feasibility and risks

---

## QA / Testing Lead

### Role Summary
QA/Testing Leads define quality standards, create test strategies, and ensure products meet acceptance criteria and user expectations. They work closely with developers and product managers to validate features before release and identify quality risks early.

### Responsibilities
- Develop test plans and acceptance criteria aligned with product requirements
- Define quality standards and testing strategies (unit, integration, end-to-end, performance)
- Create and maintain test cases and automated test suites
- Execute manual and automated testing on features before release
- Identify, document, and track quality defects and issues
- Collaborate on acceptance criteria definitions with product and development teams
- Conduct smoke tests and regression testing before releases
- Review release readiness and quality metrics

### Goals
- Reduce production defects and user-facing issues
- Deliver high-quality features that meet acceptance criteria
- Enable fast feedback cycles and continuous improvement
- Build customer confidence through thorough testing

### Typical Communication
- Sprint planning and definition of acceptance criteria discussions
- Quality review meetings and test result updates
- Defect reports and tracking via issue management system
- Pre-release quality sign-off and smoke test results
- Post-release issues and hotfix coordination

### Interactions with Other Roles
- **Developers**: Collaborate on test design, reproduce defects, and validate fixes
- **Product Manager**: Review acceptance criteria and validate feature completeness
- **Project Manager**: Report quality metrics and release readiness status
- **DevOps/Infrastructure Engineer**: Coordinate testing environments and deployments

---

## Security Lead

### Role Summary
Security Leads provide security expertise and oversight to ensure projects meet compliance, data protection, and security standards. They partner with the delivery team to identify security risks, review designs, and coordinate incident response.

### Responsibilities
- Review project plans and designs for security implications
- Conduct or coordinate security reviews and threat modeling
- Define security acceptance criteria and test plans
- Review and approve security-sensitive code changes
- Coordinate with Security incident response team for production incidents
- Document security decisions and risk mitigations in Risk Register
- Advise on compliance and data handling requirements
- Participate in security scanning and vulnerability remediation

### Goals
- Reduce security vulnerabilities in production
- Ensure compliance with organizational and regulatory standards
- Enable secure by design practices across projects
- Minimize security-related incidents and their impact

### Typical Communication
- Security design reviews during planning phase
- PR review for security-sensitive changes
- Risk Register updates for security-related risks
- Incident response coordination and post-mortems
- Quarterly security training or awareness sessions

### Interactions with Other Roles
- **Project Manager**: Escalates security risks and compliance requirements
- **Developers/Tech Lead**: Reviews designs and code for security best practices
- **QA/Testing Lead**: Defines security testing requirements
- **DevOps/Infrastructure Engineer**: Coordinates security scanning and compliance in CI/CD

---

## DevOps / Infrastructure Engineer

### Role Summary
DevOps Engineers manage infrastructure, deployment pipelines, monitoring, and operational readiness. They work with developers to enable continuous integration and deployment while ensuring system reliability and observability.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and cloud resources
- Set up monitoring, logging, and alerting for applications
- Conduct security and compliance scanning in CI
- Enable smooth and safe deployments to production
- Support incident response and post-incident analysis
- Document deployment procedures and runbooks
- Collaborate on performance optimization and capacity planning
- Ensure backup and disaster recovery procedures

### Goals
- Enable rapid, reliable delivery with minimal manual effort
- Maintain high availability and performance
- Reduce deployment risk and rollback time
- Support observability and incident resolution

### Typical Communication
- Planning discussions on infrastructure needs and constraints
- Code review for deployment scripts and infrastructure code
- Deployment coordination during release windows
- Incident response and diagnostics
- Post-deployment verification and metrics review

### Interactions with Other Roles
- **Developers**: Supports infrastructure requests and deployment automation
- **Project Manager**: Provides deployment scheduling and infrastructure constraints
- **Security Lead**: Implements security scanning and compliance in CI/CD pipelines
- **QA/Testing Lead**: Provisions test environments and coordinates pre-release testing

---

## Tech Lead / Architect

### Role Summary
Tech Leads provide technical leadership, make design decisions, and ensure solutions are scalable, maintainable, and aligned with architectural standards. They guide developers on technical approach and help identify technical risks and trade-offs.

### Responsibilities
- Drive technical design and architecture decisions
- Review and approve technical designs and PRs for architectural alignment
- Identify technical risks and propose mitigations
- Mentor and coach developers on best practices and code quality
- Ensure consistency with technology standards and patterns
- Collaborate with other teams on integration and dependency points
- Conduct technical feasibility assessments and proof-of-concepts
- Participate in retrospectives to identify technical improvements

### Goals
- Deliver scalable, maintainable, and reliable software
- Reduce technical debt and improve code quality
- Enable team growth through mentorship and knowledge sharing
- Minimize technical risks and integration issues

### Typical Communication
- Design reviews and technical decision documents
- Code review feedback and technical guidance
- Architecture documentation and decision logs
- Cross-team technical discussions and alignment
- Sprint planning for technical considerations

### Interactions with Other Roles
- **Developers**: Provides technical guidance and reviews code for quality and consistency
- **Product Manager**: Advises on technical trade-offs and feasibility
- **Project Manager**: Identifies technical dependencies and risks for the Risk Register
- **Security Lead**: Collaborates on secure design and threat modeling

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters facilitate agile ceremonies, remove blockers, and coach teams on agile practices. They help teams optimize their process, resolve conflicts, and maintain a healthy, productive working environment.

### Responsibilities
- Facilitate agile ceremonies (standups, planning, retrospectives, reviews)
- Remove impediments and blockers that slow down the team
- Coach team members on agile principles and practices
- Maintain project board and sprint artifacts
- Identify process improvements and facilitate team discussions
- Shield team from distractions and external interruptions
- Track team velocity and capacity for planning
- Escalate unresolved blockers to Project Manager

### Goals
- Enable team productivity and sustainable pace
- Improve team collaboration and communication
- Optimize sprint planning and delivery predictability
- Foster a culture of continuous improvement

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-one coaching sessions with team members
- Process improvement retrospectives
- Blocker escalations to Project Manager
- Velocity and capacity metrics reviews

### Interactions with Other Roles
- **Project Manager**: Escalates blockers and provides sprint metrics
- **Developers**: Coaches on agile practices and removes obstacles
- **Product Manager**: Coordinates on backlog priorities and sprint readiness
- **All Team Members**: Facilitates team interactions and psychological safety

---

## Stakeholder Representative / Business Analyst

### Role Summary
Stakeholder Representatives bridge business needs and delivery teams by gathering requirements, clarifying acceptance criteria, and ensuring solutions address user needs. They act as a voice of the customer and advocate for user value throughout the project.

### Responsibilities
- Gather and clarify business and user requirements
- Translate business needs into acceptance criteria and user stories
- Engage stakeholders to validate understanding and obtain feedback
- Document business rules and workflows
- Participate in design reviews to ensure user value delivery
- Validate solutions against original business objectives
- Support user acceptance testing and user feedback collection
- Communicate user impact and business value to the team

### Goals
- Ensure solutions deliver real user and business value
- Reduce misalignment between stakeholder needs and delivery
- Enable faster feature validation and user acceptance
- Maximize customer satisfaction and adoption

### Typical Communication
- Requirements gathering sessions and stakeholder interviews
- Acceptance criteria definition with product and development teams
- Design and feasibility reviews
- User acceptance testing coordination
- Feedback collection and user impact reporting

### Interactions with Other Roles
- **Product Manager**: Collaborates on prioritization and success metrics
- **Project Manager**: Communicates stakeholder expectations and feedback
- **Developers/Tech Lead**: Clarifies requirements and acceptance criteria
- **QA/Testing Lead**: Supports user acceptance testing and validation

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
