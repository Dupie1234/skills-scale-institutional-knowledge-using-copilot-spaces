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
QA/Testing Leads own the quality strategy, test planning, and acceptance validation for projects. They collaborate with product and engineering to define testability requirements and ensure features meet quality standards.

### Responsibilities
- Define and maintain test strategy (unit, integration, end-to-end, performance)
- Create and execute test plans for each iteration
- Validate acceptance criteria are met before marking work as done
- Identify and report quality issues with severity and reproduction steps
- Coordinate with developers on testability and test coverage metrics
- Review and approve test automation coverage
- Support release readiness validation and smoke testing

### Goals
- Catch defects early to reduce production incidents
- Maintain quality standards and customer trust
- Enable fast, confident releases through comprehensive testing

### Typical Communication
- Sprint planning and backlog refinement
- Daily standups to track quality blockers
- QA sign-off on PRs and features
- Release readiness reports

### Interactions with Other Roles
- **Developers**: Collaborate on test coverage, review test automation, discuss edge cases
- **Product Managers**: Clarify acceptance criteria, prioritize testing efforts
- **Project Managers**: Report quality metrics, escalate blockers that impact timeline
- **DevOps/Release Engineer**: Provide test results for deployment decisions

---

## Technical Lead/Architect

### Role Summary
Technical Leads provide technical direction, make architectural decisions, and ensure solutions align with system design principles. They mentor developers and guide technical problem-solving.

### Responsibilities
- Make or review major architectural decisions
- Conduct technical design reviews before implementation
- Identify technical risks and propose mitigations
- Mentor developers on design patterns and best practices
- Review critical pull requests for architectural alignment
- Define technical standards (coding, performance, scalability)
- Support infrastructure and performance optimization efforts

### Goals
- Ensure scalable, maintainable, and secure architecture
- Reduce technical debt and rework
- Accelerate team velocity through clear technical direction

### Typical Communication
- Technical design reviews and architecture discussions
- Code review comments on complex changes
- Mentoring and pair programming sessions
- Planning meetings to discuss technical feasibility

### Interactions with Other Roles
- **Developers**: Provide guidance, review code, mentor on patterns
- **Product Managers**: Advise on technical feasibility and trade-offs
- **DevOps/Release Engineer**: Collaborate on infrastructure and performance
- **Project Managers**: Communicate technical risks and timeline implications

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, funding, and strategic direction for projects. They remove organizational blockers and approve major decisions that impact scope, timeline, and resources.

### Responsibilities
- Fund and authorize project work
- Provide business context and success criteria alignment
- Remove organizational blockers and escalate issues
- Approve scope changes and trade-offs
- Support team through executive communications and stakeholder management
- Provide periodic project visibility and status updates to leadership

### Goals
- Ensure project delivers business value
- Maintain alignment across organizational priorities
- Remove obstacles that prevent team success

### Typical Communication
- Milestone reviews and gate approvals
- Weekly or bi-weekly status updates
- Escalation and decision-making forums
- Release announcements and business impact reporting

### Interactions with Other Roles
- **Project Managers**: Provide strategic direction and remove blockers
- **Product Managers**: Validate business outcomes and priorities
- **Developers**: Communicate timeline expectations and business context
- **All Roles**: Escalation path for decision authority

---

## DevOps/Release Engineer

### Role Summary
DevOps and Release Engineers manage CI/CD pipelines, deployment infrastructure, and release automation. They ensure reliable, repeatable deployments and maintain production observability.

### Responsibilities
- Design and maintain CI/CD pipelines and automation
- Manage deployment infrastructure (staging, production environments)
- Coordinate and execute releases following deployment checklists
- Monitor deployments and troubleshoot infrastructure issues
- Automate testing, build, and deployment processes
- Support rollback and incident response procedures
- Document deployment runbooks and procedures

### Goals
- Enable fast, reliable, and safe deployments
- Minimize downtime and deployment-related incidents
- Reduce manual work and human error in release processes

### Typical Communication
- Release coordination meetings
- Deployment readiness reviews
- Incident response and post-mortems
- Infrastructure and performance reports

### Interactions with Other Roles
- **Developers**: Coordinate on build processes, infrastructure requirements, and performance optimization
- **QA/Testing Lead**: Provide deployment verification and smoke test results
- **Project Managers**: Communicate deployment timelines and risks
- **Technical Lead/Architect**: Collaborate on infrastructure design and scalability

---

## Design/UX Lead

### Role Summary
Design and UX Leads own user experience, interface design, and usability standards. They ensure products are intuitive, accessible, and meet user needs and expectations.

### Responsibilities
- Define and maintain design systems and UI standards
- Conduct user research and gather feedback
- Create wireframes, prototypes, and design specifications
- Review designs for usability, accessibility, and consistency
- Collaborate with developers on design implementation and responsive behavior
- Define accessibility standards (WCAG compliance)
- Conduct usability testing and iterate based on feedback

### Goals
- Deliver intuitive, accessible, and delightful user experiences
- Maintain design consistency and brand alignment
- Reduce user friction and improve satisfaction

### Typical Communication
- Design reviews and critique sessions
- Usability testing findings and recommendations
- Collaboration with product on feature specifications
- Design system documentation and guidance

### Interactions with Other Roles
- **Product Managers**: Align design with product goals and user needs
- **Developers**: Support design implementation and responsive design
- **QA/Testing Lead**: Define accessibility acceptance criteria
- **Project Managers**: Communicate design timelines and review schedules

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate team ceremonies, remove process blockers, and coach teams on agile practices. They enable continuous improvement and maintain team velocity.

### Responsibilities
- Facilitate daily standups, sprint planning, reviews, and retrospectives
- Remove process blockers and impediments
- Coach team on agile practices and iterative delivery
- Track team metrics (velocity, burndown, cycle time)
- Support process improvements based on retrospective actions
- Manage sprint logistics and tooling
- Mentor team members on agile mindset and practices

### Goals
- Maintain predictable team velocity
- Enable fast, iterative delivery
- Foster a culture of continuous improvement and psychological safety

### Typical Communication
- Daily standups and ceremony facilitation
- Sprint planning and retrospective notes
- Team velocity and burndown reports
- Impediment escalations and tracking

### Interactions with Other Roles
- **Project Managers**: Coordinate on timeline and scope management
- **Product Managers**: Support backlog refinement and prioritization
- **All Team Members**: Coach on agile practices and remove blockers

---

## Security/Compliance Officer

### Role Summary
Security and Compliance Officers ensure security requirements are met, compliance standards are followed, and security risks are managed throughout the project lifecycle.

### Responsibilities
- Define security and compliance requirements for projects
- Conduct security threat assessments and risk analysis
- Review architectural and design decisions for security implications
- Conduct or coordinate security reviews (code, infrastructure, design)
- Manage security incident response and post-mortems
- Ensure compliance with regulatory standards (SOC 2, HIPAA, GDPR, etc.)
- Provide security guidance and best practices to team
- Track security metrics and remediation timelines

### Goals
- Prevent security incidents and data breaches
- Maintain compliance with regulatory and organizational standards
- Enable secure development without blocking team velocity

### Typical Communication
- Security design reviews and threat assessments
- Compliance audit and certification updates
- Incident response and post-mortem reports
- Security training and guidance documentation

### Interactions with Other Roles
- **Developers**: Provide security guidance, review code and PRs for security concerns
- **Technical Lead/Architect**: Review architectural decisions for security implications
- **DevOps/Release Engineer**: Ensure secure deployment practices and infrastructure hardening
- **Project Managers**: Communicate security timelines and blockers

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
