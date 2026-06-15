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

## Additional Personas and Suggested Responsibilities

### Delivery Lead

**Role Summary**
The Delivery Lead coordinates day-to-day delivery activities and acts as a liaison between the Project Manager and the delivery team. They manage sprint-level execution, risks, and dependencies to keep work moving smoothly.

**Responsibilities**
- Coordinate day-to-day delivery activities with the PM
- Manage sprint-level risks and dependencies
- Maintain the delivery schedule and sprint cadence
- Ensure blockers are identified, escalated, and resolved quickly
- Facilitate standups and sprint ceremonies
- Track team velocity and capacity

**Goals**
- Keep the team unblocked and focused on delivery
- Maintain predictability in sprint execution
- Reduce rework and schedule slippage

**Typical Interactions**
- Works closely with PM (scheduling/risks), Developers (capacity and coordination), QA (handoff and testing readiness), and Product (scope adjustments and prioritization changes)

---

### UX Researcher / Designer

**Role Summary**
UX Researchers and Designers lead user research, define user-centered acceptance criteria, produce designs and prototypes, and validate usability before release. They ensure the product is not just functional but also intuitive and delightful.

**Responsibilities**
- Lead user research and user testing activities
- Define UX acceptance criteria aligned with user needs
- Produce designs, wireframes, and interactive prototypes
- Validate usability and gather feedback before and after release
- Document design decisions and maintain design systems
- Collaborate on accessibility and inclusive design

**Goals**
- Deliver products that are intuitive and meet user needs
- Reduce rework caused by unclear or misaligned design
- Ensure accessibility and inclusive design practices

**Typical Interactions**
- Partners with Product Manager (requirements & success metrics), Developers (design implementation), QA (usability and exploratory testing), and Stakeholders (feedback cycles and validation)

---

### Release Manager

**Role Summary**
The Release Manager owns the end-to-end release process, including coordination, deployment windows, rollback strategies, release notes, and post-release verification. They reduce risk and ensure smooth handoffs to production.

**Responsibilities**
- Own release coordination and planning
- Manage deployment windows and scheduling
- Develop and execute rollback strategies and contingency plans
- Draft and publish release notes
- Conduct post-release verification and smoke tests
- Communicate release status to stakeholders and support teams
- Track and manage known issues and hotfixes

**Goals**
- Reduce release risk and cycle time
- Ensure deployments are predictable and well-coordinated
- Maintain transparency and fast incident response

**Typical Interactions**
- Coordinates with PM (scope confirmation), DevOps/Platform/SRE (deployment execution), Security (security sign-off), Support (customer impact planning), and Stakeholders (release announcements)

---

### Security & Compliance Liaison

**Role Summary**
The Security & Compliance Liaison assesses security and compliance impacts of proposed changes, coordinates required security reviews and scans, and approves changes that affect the security or compliance posture of the product.

**Responsibilities**
- Assess security and compliance impacts of features and changes
- Run or coordinate security reviews and automated scans
- Identify and prioritize security vulnerabilities and remediation steps
- Approve changes that affect compliance posture (e.g., data handling, encryption, user privacy)
- Maintain security and compliance documentation
- Escalate critical security issues and manage incident response

**Goals**
- Prevent security and compliance regressions
- Integrate security into the development process early (shift-left)
- Maintain customer trust and regulatory compliance

**Typical Interactions**
- Works with Developers (remediations and secure coding practices), PM (risk decisions and trade-offs), and Security/Legal/Compliance teams (approvals and oversight)

---

### Data Analyst / Metrics Owner

**Role Summary**
The Data Analyst owns the measurement plan, builds dashboards, analyzes the impact of releases against success metrics, and instruments the product to capture key signals. They provide the data foundation for product decisions.

**Responsibilities**
- Define and maintain a comprehensive measurement plan
- Identify and instrument key success metrics
- Build and maintain dashboards for team and stakeholder visibility
- Analyze impact of releases against success metrics
- Conduct post-release analysis and provide insights
- Collaborate on experiment design and A/B testing strategies

**Goals**
- Enable data-driven decision making
- Ensure visibility into product performance and user behavior
- Reduce guesswork and validate assumptions

**Typical Interactions**
- Partners with Product Manager (success metrics and measurement priorities), Developers (instrumentation implementation), and Stakeholders (reporting and insights)

---

### Technical Writer / Documentation Owner

**Role Summary**
The Technical Writer owns user-facing and internal documentation, ensuring that release notes, runbooks, API docs, and user guides are accurate, up-to-date, and accessible. They reduce support burden and enable self-service.

**Responsibilities**
- Maintain user-facing documentation and help articles
- Draft and update release notes for each release
- Create and maintain operational runbooks and playbooks
- Document APIs, SDKs, and integration guides
- Ensure documentation is accessible and easy to understand
- Coordinate with Support on frequently asked questions and documentation gaps

**Goals**
- Reduce support burden through self-service documentation
- Ensure users can effectively use the product
- Maintain accuracy and consistency in all documentation

**Typical Interactions**
- Works with Product Manager (content accuracy and feature descriptions), Developers (technical details and implementation), and Support (customer-facing documentation and gaps)

---

### Platform / SRE (Observability Engineer)

**Role Summary**
The Platform/SRE team ensures platform stability, reliability, and observability. They own monitoring, alerting, runbooks, and respond to operational incidents. They partner with developers to instrument systems effectively.

**Responsibilities**
- Ensure monitoring, alerting, and observability best practices
- Build and maintain runbooks for common incidents and operational tasks
- Own platform reliability metrics (uptime, latency, error rates)
- Respond to and triage operational incidents
- Perform post-incident reviews and capture action items
- Partner with developers on instrumentation and logging
- Manage infrastructure and deployment infrastructure

**Goals**
- Maintain high platform reliability and uptime
- Enable fast incident response and debugging
- Reduce mean time to recovery (MTTR) for incidents

**Typical Interactions**
- Coordinates with Developers (instrumentation, logging, and incident debugging), Release Manager (deploy readiness and rollback execution), PM (incident communication and impact assessment), and Stakeholders (incident transparency)

---

## How these personas are used in the exercise

- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When staffing a project, ensure representation of both core roles (Developer, Product Manager, Project Manager) and complementary personas based on project complexity and scope.
- Use the interaction patterns to understand cross-functional dependencies and communication needs.
