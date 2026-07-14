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
QA/Testing Leads own the quality assurance strategy, test planning, and validation of acceptance criteria throughout the project lifecycle. They collaborate with product, engineering, and stakeholders to ensure delivery meets quality standards.

### Responsibilities
- Define and maintain test strategy and test plans
- Create and prioritize test cases aligned to acceptance criteria
- Execute manual and automated testing
- Report quality metrics and defect tracking
- Coordinate with developers on test automation and CI integration
- Validate acceptance criteria with Product Managers before sign-off
- Participate in planning to estimate QA effort

### Goals
- Ensure high-quality releases with minimal defects
- Provide clear visibility into quality status
- Reduce time to delivery through efficient test execution
- Foster quality mindset across the team

### Typical Communication
- Sprint planning and retrospectives
- Daily standups (status, blockers, dependencies)
- Defect triage and root cause analysis meetings
- Pre-release readiness reviews

---

## Technical Lead / Architect

### Role Summary
Technical Leads provide architectural oversight, review technical decisions, and help identify risks and dependencies. They work closely with developers to ensure technical excellence and alignment with system design.

### Responsibilities
- Define or refine technical architecture and design patterns
- Review design documents and code architecture decisions
- Identify technical risks, dependencies, and trade-offs
- Mentor developers and help resolve technical blockers
- Ensure adherence to coding standards and best practices
- Collaborate on capacity planning and technology decisions
- Participate in retrospectives to drive technical improvements

### Goals
- Deliver scalable, maintainable, and secure systems
- Reduce technical debt and rework
- Enable team learning and growth
- Minimize architectural risks

### Typical Communication
- Technical design review sessions
- Code review and architecture discussions
- Sprint planning (technical feasibility assessment)
- Risk registers and dependency tracking

---

## Scrum Master / Agile Coach

### Role Summary
Scrum Masters and Agile Coaches facilitate iterative delivery processes, remove impediments, and help teams continuously improve their practices. They serve as guardians of the process and enablers of team autonomy.

### Responsibilities
- Facilitate agile ceremonies (standups, planning, reviews, retrospectives)
- Identify and help resolve process blockers and impediments
- Coach team on agile practices and continuous improvement
- Maintain project board and artifact hygiene
- Support team velocity tracking and process metrics
- Help teams self-organize and make decisions
- Escalate blockers that cannot be resolved at team level

### Goals
- Enable consistent, predictable delivery
- Improve team velocity and efficiency over time
- Foster psychological safety and continuous learning
- Reduce process-related delays and rework

### Typical Communication
- Sprint ceremonies and retrospectives
- One-on-ones with team members
- Process improvement discussions
- Metrics and velocity tracking reviews

---

## Operations / DevOps Engineer

### Role Summary
Operations and DevOps Engineers manage deployment pipelines, infrastructure, monitoring, and post-deployment verification. They enable reliable, automated, and observable releases to production.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure, environments, and deployments
- Implement monitoring, logging, and alerting
- Execute deployments and coordinate rollback procedures
- Perform post-deployment verification and smoke testing
- Document runbooks and incident playbooks
- Collaborate with development on deployment and infrastructure requirements

### Goals
- Enable fast, reliable, and automated deployments
- Minimize deployment-related incidents and rollbacks
- Provide observability into system health and performance
- Reduce manual effort through automation

### Typical Communication
- Release planning and pre-deployment checklists
- Deployment windows and post-deploy verification
- Incident response and escalation
- Infrastructure planning and capacity discussions

---

## Security / Compliance Officer

### Role Summary
Security and Compliance Officers ensure that security and regulatory requirements are met throughout the project lifecycle. They conduct security reviews, manage compliance concerns, and help teams adopt secure development practices.

### Responsibilities
- Define and communicate security and compliance requirements
- Review security scanning results and manage remediation
- Conduct security architecture and code reviews
- Manage vulnerability tracking and incident response
- Ensure compliance with relevant standards and regulations
- Provide security training and guidance to the team
- Approve security exceptions and risk acceptances

### Goals
- Protect customer data and system integrity
- Minimize security vulnerabilities and breaches
- Ensure compliance with regulatory requirements
- Foster security-first mindset across teams

### Typical Communication
- Security requirements in planning and design reviews
- Security scanning results and remediation tracking
- Incident response and post-incident reviews
- Compliance audit and risk assessments

---

## Business Analyst

### Role Summary
Business Analysts bridge the gap between business needs and technical delivery. They gather, document, and validate requirements to ensure alignment between stakeholders and the delivery team.

### Responsibilities
- Gather and document business requirements from stakeholders
- Translate business needs into clear, testable acceptance criteria
- Create and maintain requirements documentation
- Validate solutions against business requirements
- Clarify scope and identify requirements gaps
- Participate in design and planning to ensure feasibility
- Support user acceptance testing and solution validation

### Goals
- Ensure delivery meets business needs and expectations
- Reduce scope creep and requirements misalignment
- Improve communication between business and technical teams
- Enable faster time-to-value through clear requirements

### Typical Communication
- Stakeholder interviews and requirements gathering sessions
- Requirements documentation and acceptance criteria
- Design reviews and feasibility discussions
- UAT coordination and feedback integration

---

## Interaction Matrix: How Roles Work Together

| Primary Role | Collaborates With | On What |
|---|---|---|
| **Developer** | Tech Lead, QA Lead, DevOps | Design reviews, code quality, deployment readiness |
| **Product Manager** | PM, Business Analyst | Backlog prioritization, success metrics, requirements validation |
| **Project Manager** | All roles | Scheduling, risk management, status reporting, escalation |
| **QA Lead** | Developer, Product Manager, Business Analyst | Test strategy, acceptance criteria, quality gates |
| **Tech Lead** | Developer, Architect, DevOps | Architecture decisions, technical risks, design standards |
| **Scrum Master** | All roles | Process facilitation, impediment removal, retrospectives |
| **DevOps Engineer** | Developer, Tech Lead, Sec/Compliance | Deployment readiness, infrastructure requirements, monitoring |
| **Security Officer** | Tech Lead, Developer, DevOps | Security requirements, vulnerability management, compliance |
| **Business Analyst** | Product Manager, Stakeholders, QA | Requirements clarity, scope definition, solution validation |

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- Refer to the Interaction Matrix to understand cross-functional collaboration patterns.
