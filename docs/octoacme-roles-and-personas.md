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

## QA Engineers

### Role Summary
QA Engineers validate that features meet acceptance criteria, quality standards, and usability expectations. They collaborate with Developers and Product Managers to ensure releases are reliable and defect-free.

### Responsibilities
- Design and execute test plans for new features and regression testing
- Report, track, and verify defect resolution
- Perform exploratory testing and usability validation
- Work with Developers to improve testability and automation
- Validate acceptance criteria with Product Managers before sign-off

### Goals
- Ensure product quality and reliability before release
- Reduce production defects through comprehensive testing
- Improve test coverage and automation

### Typical Interactions
- **With Developers**: Review acceptance criteria during sprint planning; collaborate on test automation; report and validate defect fixes
- **With Product Managers**: Clarify acceptance criteria; provide feedback on usability; escalate quality concerns
- **With Project Managers**: Report testing status; flag risks that may impact release timelines
- **With Stakeholders**: Provide quality assessments before major releases

### Typical Communication
- Test reports and defect status updates
- Sign-off on feature acceptance
- QA retrospectives and lessons learned

---

## Stakeholders

### Role Summary
Stakeholders are business leaders, subject matter experts, and representatives who provide input, approvals, and resources to ensure projects align with business goals.

### Responsibilities
- Define business requirements and constraints
- Provide approvals at key decision gates
- Review progress and impact on business operations
- Escalate issues or resource needs
- Champion project outcomes within their organization

### Goals
- Ensure projects deliver measurable business value
- Protect business interests and compliance requirements
- Maintain visibility into project status and risks

### Typical Interactions
- **With Product Managers**: Validate roadmap priorities; provide business context and success criteria
- **With Project Managers**: Receive status updates; approve scope changes; escalate blockers
- **With Developers**: Provide domain expertise during design; participate in demos
- **With QA**: Review quality metrics before major releases

### Typical Communication
- Monthly status reviews and milestone updates
- Decision logs and approval records
- Escalations for high-impact issues

---

## UX Designer

### Role Summary
UX Designers create user-centered experiences through research, design, and validation. They ensure products are intuitive, accessible, and aligned with user needs.

### Responsibilities
- Conduct user research and usability testing
- Create wireframes, mockups, and interactive prototypes
- Define design systems and ensure visual consistency
- Collaborate with Developers on implementation feasibility
- Validate designs through user feedback and A/B testing
- Ensure accessibility standards (WCAG) are met

### Goals
- Deliver delightful, intuitive user experiences
- Reduce user friction and support costs
- Ensure accessibility and inclusive design

### Typical Interactions
- **With Product Managers**: Translate product requirements into user flows; validate designs against success metrics
- **With Developers**: Review technical constraints; provide design specs and assets; validate implementation quality
- **With QA**: Define usability test cases; participate in acceptance testing
- **With Stakeholders**: Present design concepts; gather feedback on user experience
- **With Data Analyst**: Use analytics to identify usability issues; validate design improvements

### Handoffs and Accountability
- **From Product Manager**: User stories and acceptance criteria
- **To Developers**: Design specs, assets, and style guides
- **To QA**: Usability test plans and expected behaviors

### Typical Communication
- Design reviews and stakeholder presentations
- User research findings and usability reports
- Design system documentation and component libraries

---

## Data Analyst

### Role Summary
Data Analysts provide insights through data collection, analysis, and reporting. They help teams make informed decisions and measure product success.

### Responsibilities
- Define and track key performance indicators (KPIs)
- Build dashboards and reporting tools
- Analyze user behavior and feature adoption
- Identify trends, anomalies, and opportunities
- Support A/B testing and experimentation
- Ensure data quality and governance

### Goals
- Enable data-driven decision making
- Measure and communicate product impact
- Identify opportunities for improvement through data insights

### Typical Interactions
- **With Product Managers**: Define success metrics; provide data on feature performance and user behavior
- **With Developers**: Implement tracking and instrumentation; troubleshoot data quality issues
- **With UX Designer**: Share user behavior data; support usability testing with analytics
- **With Stakeholders**: Present business metrics; provide ROI and impact reports
- **With Project Managers**: Track project health metrics; identify risks through data trends

### Handoffs and Accountability
- **From Product Manager**: Success metrics and measurement framework
- **To Product Manager & Stakeholders**: Analytics reports and insights
- **To Developers**: Instrumentation requirements and data schemas

### Typical Communication
- Weekly/monthly metrics reports and dashboards
- Ad-hoc analysis for feature validation
- Data quality alerts and anomaly reports

---

## DevOps Engineer

### Role Summary
DevOps Engineers build and maintain infrastructure, CI/CD pipelines, and monitoring systems. They enable rapid, reliable deployments while ensuring system stability and security.

### Responsibilities
- Design and maintain CI/CD pipelines
- Manage infrastructure as code (IaC) and cloud resources
- Implement monitoring, logging, and alerting systems
- Ensure security best practices in deployment processes
- Respond to incidents and performance issues
- Automate operational tasks and reduce toil

### Goals
- Enable fast, reliable deployments with minimal manual intervention
- Maintain high availability and system reliability
- Improve developer productivity through automation

### Typical Interactions
- **With Developers**: Provide deployment tools and environments; troubleshoot build/deployment issues; review infrastructure needs
- **With QA**: Set up test environments; provide access to logs and monitoring
- **With Project Managers**: Report on deployment readiness; flag infrastructure risks and capacity constraints
- **With Stakeholders**: Present uptime metrics and incident reports
- **With Legal/Compliance Advisor**: Implement security controls; ensure audit logging and compliance requirements

### Handoffs and Accountability
- **From Developers**: Application code, deployment requirements, and resource needs
- **To Developers**: CI/CD pipelines, deployment documentation, and environment access
- **To Project Managers**: Infrastructure status and deployment schedules

### Typical Communication
- Incident reports and postmortems
- Infrastructure change notifications
- SLO/SLA reports and capacity planning updates

---

## Agile Coach

### Role Summary
Agile Coaches guide teams in adopting and improving agile practices. They facilitate collaboration, continuous improvement, and help remove organizational impediments.

### Responsibilities
- Coach teams on agile principles and practices (Scrum, Kanban, etc.)
- Facilitate ceremonies (standups, retrospectives, sprint planning)
- Help teams identify and remove impediments
- Promote collaboration and psychological safety
- Guide continuous improvement through retrospectives
- Support organizational agile transformation

### Goals
- Improve team velocity and predictability
- Foster self-organizing, high-performing teams
- Create culture of continuous learning and improvement

### Typical Interactions
- **With Project Managers**: Coach on facilitation techniques; help optimize project workflows and ceremonies
- **With Developers**: Remove blockers; improve team dynamics and collaboration
- **With Product Managers**: Optimize backlog refinement; improve story writing and acceptance criteria
- **With QA**: Integrate testing into agile workflow; promote shift-left quality practices
- **With Stakeholders**: Educate on agile principles; manage expectations around iterative delivery

### Handoffs and Accountability
- **From Project Manager**: Team health concerns and process improvement needs
- **To All Roles**: Retrospective action items and process recommendations
- **To Project Manager**: Team maturity assessments and improvement roadmaps

### Typical Communication
- Retrospective facilitation and action items
- Team health assessments and improvement plans
- Agile training and workshops

---

## Legal/Compliance Advisor

### Role Summary
Legal/Compliance Advisors ensure projects meet regulatory requirements, legal obligations, and company policies. They provide guidance on data privacy, security, contracts, and risk mitigation.

### Responsibilities
- Review features for legal and compliance risks
- Ensure data privacy regulations (GDPR, CCPA, etc.) are met
- Provide guidance on terms of service, licensing, and contracts
- Review security controls and audit requirements
- Advise on intellectual property and open-source usage
- Support incident response for data breaches or compliance issues

### Goals
- Ensure legal and regulatory compliance
- Minimize legal and compliance risks
- Enable innovation while protecting the organization

### Typical Interactions
- **With Product Managers**: Review new features for compliance requirements; advise on data handling practices
- **With Developers**: Review data collection, storage, and processing; ensure secure coding practices
- **With DevOps Engineer**: Validate security controls; review audit logging and data retention policies
- **With QA**: Define compliance test cases; validate security and privacy controls
- **With Stakeholders**: Report on compliance status; escalate regulatory risks

### Handoffs and Accountability
- **From Product Manager**: Feature requirements and data handling specifications
- **To Product Manager & Project Manager**: Compliance requirements and approval gates
- **To Developers**: Security and privacy implementation requirements

### Typical Communication
- Compliance reviews and approval records
- Risk assessments and mitigation plans
- Regulatory updates and training materials

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [Role-Based Onboarding Checklist](./octoacme-role-onboarding-checklist.md) for persona-specific onboarding activities.
- See [Collaboration Scenarios](./octoacme-collaboration-scenarios.md) for examples of cross-role interactions.

