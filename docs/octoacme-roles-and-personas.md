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

### How they interact
- Work with Technical Lead/Architect on design guidance and code reviews
- Collaborate with QA/Testing Lead on test design and acceptance criteria
- Coordinate with DevOps/Release Engineer on deployment and observability
- Receive direction from Project Manager on priorities and timelines
- Work with Product Manager on acceptance criteria and requirements

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

### How they interact
- Partner with Project Manager on timeline and resource planning
- Work with QA/Testing Lead to define acceptance criteria
- Collaborate with Technical Lead/Architect on feasibility and trade-offs
- Guide Developers on requirements and acceptance criteria
- Report to Stakeholders/Sponsors on progress and key metrics

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

### How they interact
- Align with Product Manager on priorities and scope
- Track progress with Developers and Technical Lead
- Coordinate with QA/Testing Lead on testing timelines
- Work with DevOps/Release Engineer on deployment scheduling
- Escalate risks and blockers to Stakeholders/Sponsors
- Facilitate communication between all team roles

---

## QA/Testing Lead

### Role Summary
QA/Testing Leads own the quality strategy, test planning, and acceptance validation. They work closely with Product Managers and Developers to define acceptance criteria and ensure features meet quality standards before release.

### Responsibilities
- Define test strategy and test plan for each release
- Create and maintain acceptance criteria with Product Manager and Developers
- Design and execute unit, integration, and end-to-end test cases
- Lead manual QA and acceptance testing when needed
- Track defects and quality metrics (test coverage, pass rates)
- Participate in release readiness reviews

### Goals
- Minimize defects reaching production
- Ensure features meet acceptance criteria and user expectations
- Provide clear quality signals to team and stakeholders

### Typical Communication
- Planning sessions to define acceptance criteria
- Sprint standups and backlog refinement
- Test reports and quality dashboards
- Release readiness gates

### How they interact
- Works with Product Manager to translate requirements into testable criteria
- Collaborates with Developers on test design and coverage
- Provides input to Project Manager on quality risks and test timeline
- Supports DevOps/Release Engineer on production smoke tests
- Alerts Technical Lead/Architect to quality implications of architectural decisions
- Reports quality metrics to Stakeholders/Sponsors

---

## Technical Lead/Architect

### Role Summary
Technical Leads set technical direction, guide architectural decisions, and ensure code quality and maintainability. They mentor developers and manage technical debt.

### Responsibilities
- Design system architecture and technical approach for features
- Lead technical design reviews and code reviews
- Mentor developers and provide technical guidance
- Identify and track technical debt and improvement opportunities
- Ensure scalability, security, and performance standards
- Advise on technology choices and dependencies

### Goals
- Deliver scalable, maintainable, secure solutions
- Accelerate team velocity through clear technical direction
- Build team technical capability and knowledge sharing

### Typical Communication
- Technical design docs and ADRs (Architecture Decision Records)
- Code review comments and mentoring
- Technical risk identification and mitigation planning
- Technology roadmap and dependency management

### How they interact
- Partners with Product Manager on feasibility and trade-offs
- Guides Developers on technical approaches and standards
- Identifies risks and dependencies for Project Manager escalation
- Collaborates with DevOps/Release Engineer on deployment considerations
- Works with Security/Compliance Officer on security architecture
- Reviews testing approach with QA/Testing Lead
- Advises Project Manager on technical risks and mitigation

---

## Scrum Master/Agile Coach

### Role Summary
Scrum Masters/Agile Coaches facilitate the team's delivery process, remove blockers, and coach the team on continuous improvement. They ensure ceremonies are effective and help the team adapt processes as needed.

### Responsibilities
- Facilitate sprint planning, standups, reviews, and retrospectives
- Identify and help remove blockers and impediments
- Coach the team on Agile principles and practices
- Track sprint health, velocity, and burndown
- Identify process improvement opportunities
- Escalate organizational blockers that impact the team

### Goals
- Enable the team to deliver consistently and predictably
- Create psychological safety and continuous improvement culture
- Reduce process friction and waste

### Typical Communication
- Daily standups and sprint ceremonies
- One-on-ones with team members for coaching
- Process improvement discussions and retro action items
- Escalation communication with management

### How they interact
- Partners with Project Manager on schedule and communication planning
- Coaches all team members on process adherence and improvement
- Works with Technical Lead/Architect and QA/Testing Lead on ceremony effectiveness
- Helps remove blockers identified by Developers and other roles
- Supports Stakeholders/Sponsors by communicating team health and impediments
- Facilitates communication and alignment across cross-functional teams

---

## Stakeholder/Sponsor

### Role Summary
Stakeholders and Sponsors provide business context, strategic direction, and resource authority. They approve scope changes, remove organizational blockers, and ensure alignment with business objectives.

### Responsibilities
- Define business goals and success criteria aligned with strategy
- Approve project scope, timeline, and resource allocation
- Make go/no-go decisions at key gates
- Remove organizational blockers and provide access to cross-functional teams
- Review and approve scope changes and trade-offs
- Ensure project alignment with broader business priorities

### Goals
- Ensure business value delivery and ROI
- Enable successful project execution and team autonomy
- Make informed decisions based on clear project status

### Typical Communication
- Monthly or milestone-based stakeholder updates
- Go/no-go decision meetings
- Risk escalation and mitigation planning
- Budget and resource approval meetings

### How they interact
- Receives status and risk reports from Project Manager
- Reviews success metrics and outcomes with Product Manager
- Approves resource allocation and scope changes recommended by team
- Removes organizational barriers identified by Scrum Master or Project Manager
- Communicates business priorities to Product Manager
- Provides final approval for releases through DevOps/Release Engineer

---

## Security/Compliance Officer

### Role Summary
Security/Compliance Officers ensure that projects meet security and regulatory requirements. They guide secure design practices and verify compliance before release.

### Responsibilities
- Define security requirements and compliance standards for projects
- Review and approve security architecture with Technical Lead/Architect
- Conduct or oversee security testing and vulnerability assessments
- Ensure compliance with regulatory requirements and organizational policies
- Provide security guidance during design and implementation
- Verify security readiness before release

### Goals
- Prevent security vulnerabilities and compliance violations
- Embed security and compliance into the development process
- Maintain organizational reputation and reduce risk

### Typical Communication
- Security design reviews and threat modeling sessions
- Security scanning and assessment reports
- Compliance checklists and sign-offs
- Incident response and remediation planning

### How they interact
- Partners with Technical Lead/Architect on secure system design
- Collaborates with Developers on secure coding practices
- Works with QA/Testing Lead on security test planning
- Provides security requirements to Product Manager
- Reviews release readiness with DevOps/Release Engineer
- Reports compliance status to Stakeholders/Sponsors

---

## DevOps/Release Engineer

### Role Summary
DevOps/Release Engineers manage deployment pipelines, infrastructure, and release processes. They ensure reliable, safe deployments and maintain production stability.

### Responsibilities
- Design and maintain CI/CD pipelines and infrastructure
- Manage release scheduling and deployment processes
- Conduct pre-release and post-deployment verification
- Monitor production health and manage incidents
- Document deployment procedures and runbooks
- Coordinate rollbacks when needed

### Goals
- Enable fast, safe, reliable deployments to production
- Maintain production stability and minimize downtime
- Reduce deployment risk through automation and verification

### Typical Communication
- Release planning and deployment windows
- Pre-deployment checklists and post-deployment verification
- Production monitoring and incident alerts
- Infrastructure and pipeline improvement discussions

### How they interact
- Coordinates with Project Manager on deployment scheduling
- Works with Developers on CI/CD pipeline and code quality gates
- Partners with Technical Lead/Architect on infrastructure and deployment architecture
- Collaborates with QA/Testing Lead on smoke tests and production verification
- Reports deployment status and production health to Project Manager
- Supports Security/Compliance Officer on infrastructure security
- Executes releases approved by Stakeholders/Sponsors

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- The "How they interact" sections show the interdependencies and communication patterns across all roles in the OctoAcme project management framework.
