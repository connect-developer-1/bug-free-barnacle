# OctoAcme Collaboration Scenarios

## Purpose
This document provides concrete examples of cross-role interactions to clarify handoffs, accountability, and collaborative workflows within OctoAcme projects.

---

## Scenario 1: Feature Planning and Design

### Context
The Product Manager has identified a new feature to improve user onboarding based on customer feedback.

### Workflow

1. **Product Manager → UX Designer**
   - **Handoff**: User stories, success metrics, and target personas
   - **Interaction**: PM briefs UX Designer on customer pain points and business goals
   - **Deliverable**: UX Designer creates user research plan

2. **UX Designer → Data Analyst**
   - **Interaction**: UX Designer requests analytics on current onboarding funnel and drop-off points
   - **Deliverable**: Data Analyst provides user behavior analysis and identifies friction points

3. **UX Designer → Product Manager**
   - **Handoff**: Wireframes, user flows, and design concepts
   - **Interaction**: Design review meeting to validate approach against success metrics
   - **Deliverable**: Approved design direction

4. **UX Designer → Developers**
   - **Handoff**: High-fidelity mockups, design specs, and component specifications
   - **Interaction**: Design handoff session to review implementation approach and technical constraints
   - **Deliverable**: Design assets and annotated specs in shared tool (Figma, Zeplin)

5. **Developers ↔ UX Designer**
   - **Interaction**: Clarification questions during implementation; design review of implemented UI
   - **Accountability**: Developers accountable for pixel-perfect implementation; UX Designer validates final output

6. **Product Manager → QA Engineers**
   - **Handoff**: Acceptance criteria including usability requirements
   - **Interaction**: Sprint planning discussion of testability and edge cases
   - **Deliverable**: QA creates test plan including usability validation

7. **UX Designer → QA Engineers**
   - **Handoff**: Expected user behaviors and interaction patterns
   - **Interaction**: QA validates design implementation and reports usability issues
   - **Accountability**: QA signs off on usability acceptance criteria

---

## Scenario 2: Deployment Pipeline Setup

### Context
A new microservice needs to be deployed with proper CI/CD, monitoring, and security controls.

### Workflow

1. **Developers → DevOps Engineer**
   - **Handoff**: Application requirements (runtime, dependencies, resource needs)
   - **Interaction**: Technical planning session to discuss deployment strategy
   - **Deliverable**: DevOps Engineer creates deployment pipeline design

2. **DevOps Engineer → Legal/Compliance Advisor**
   - **Interaction**: Review security controls, audit logging, and data retention requirements
   - **Deliverable**: Compliance checklist for deployment infrastructure

3. **Legal/Compliance Advisor → DevOps Engineer**
   - **Handoff**: Security requirements (encryption, access controls, audit logs)
   - **Accountability**: DevOps Engineer implements required security controls

4. **DevOps Engineer → Developers**
   - **Handoff**: CI/CD pipeline, deployment documentation, environment access
   - **Interaction**: Training session on deployment process and troubleshooting
   - **Deliverable**: Developers can independently deploy to staging environments

5. **DevOps Engineer → QA Engineers**
   - **Handoff**: Test environment setup with monitoring and log access
   - **Interaction**: QA provides feedback on test environment needs
   - **Accountability**: DevOps maintains stable test environments

6. **DevOps Engineer → Project Manager**
   - **Interaction**: Status updates on infrastructure readiness; escalation of capacity or timeline risks
   - **Deliverable**: Deployment schedule and readiness report

---

## Scenario 3: Data-Driven Feature Validation

### Context
A new feature has been released and needs validation against success metrics.

### Workflow

1. **Product Manager → Data Analyst**
   - **Handoff**: Success metrics, hypotheses to validate, target timelines
   - **Interaction**: Planning meeting to define measurement framework
   - **Deliverable**: Data Analyst creates tracking plan and dashboard spec

2. **Data Analyst → Developers**
   - **Handoff**: Instrumentation requirements and event schema
   - **Interaction**: Code review to ensure proper tracking implementation
   - **Accountability**: Developers implement tracking; Data Analyst validates data quality

3. **Developers → Data Analyst**
   - **Handoff**: Deployed feature with instrumentation
   - **Interaction**: Data Analyst validates that events are firing correctly in production
   - **Deliverable**: Data quality sign-off

4. **Data Analyst → Product Manager**
   - **Handoff**: Analytics dashboard and performance reports
   - **Interaction**: Weekly review of feature performance against success metrics
   - **Accountability**: Data Analyst provides accurate, timely insights

5. **Data Analyst → UX Designer**
   - **Interaction**: Share user behavior patterns and usability insights from analytics
   - **Deliverable**: Data-driven recommendations for design improvements

6. **Product Manager → Stakeholders**
   - **Handoff**: Feature impact report with data insights
   - **Interaction**: Monthly stakeholder review of product metrics
   - **Accountability**: Product Manager owns business outcomes

---

## Scenario 4: Agile Process Improvement

### Context
The team is experiencing frequent scope creep and sprint commitment issues.

### Workflow

1. **Project Manager → Agile Coach**
   - **Interaction**: Escalation of team health concern and request for coaching support
   - **Deliverable**: Agile Coach observes team ceremonies and conducts health assessment

2. **Agile Coach → Team Members**
   - **Interaction**: One-on-one conversations to understand pain points and dynamics
   - **Deliverable**: Team health assessment with identified impediments

3. **Agile Coach → Project Manager**
   - **Handoff**: Recommendations for process improvements (better story writing, improved estimation)
   - **Accountability**: Agile Coach facilitates implementation; Project Manager ensures follow-through

4. **Agile Coach → Product Manager**
   - **Interaction**: Coaching on backlog refinement and acceptance criteria clarity
   - **Deliverable**: Improved story templates and Definition of Ready

5. **Agile Coach → Developers & QA**
   - **Interaction**: Workshop on estimation techniques and Definition of Done
   - **Deliverable**: Team alignment on estimation and commitment practices

6. **Agile Coach (Facilitates) → All Team Members**
   - **Interaction**: Retrospective focused on commitment and scope management
   - **Deliverable**: Action items with owners and timelines

7. **Agile Coach → Project Manager**
   - **Handoff**: Team maturity assessment and improvement roadmap
   - **Accountability**: Agile Coach monitors progress; Project Manager tracks action item completion

---

## Scenario 5: Compliance Review for New Feature

### Context
A new feature will collect and process user personal data, requiring compliance review.

### Workflow

1. **Product Manager → Legal/Compliance Advisor**
   - **Handoff**: Feature requirements document with data handling details
   - **Interaction**: Early consultation during feature planning phase
   - **Deliverable**: Legal/Compliance Advisor provides initial risk assessment

2. **Legal/Compliance Advisor → Product Manager**
   - **Handoff**: Compliance requirements (consent mechanisms, data minimization, retention policies)
   - **Accountability**: Product Manager incorporates compliance requirements into acceptance criteria

3. **Legal/Compliance Advisor → Developers**
   - **Handoff**: Technical requirements for compliance (encryption, anonymization, audit logging)
   - **Interaction**: Design review to validate compliance approach
   - **Deliverable**: Developers implement compliant data handling

4. **Legal/Compliance Advisor → DevOps Engineer**
   - **Interaction**: Review infrastructure security controls and audit logging
   - **Deliverable**: DevOps Engineer implements required security measures

5. **Legal/Compliance Advisor → QA Engineers**
   - **Handoff**: Compliance test cases (consent flows, data deletion, privacy controls)
   - **Interaction**: QA includes compliance validation in test plan
   - **Accountability**: QA validates compliance requirements before release

6. **Legal/Compliance Advisor → Project Manager**
   - **Interaction**: Compliance approval gate before release
   - **Deliverable**: Formal compliance sign-off document

7. **Legal/Compliance Advisor → Stakeholders**
   - **Interaction**: Report on compliance status and any residual risks
   - **Accountability**: Legal/Compliance Advisor ensures regulatory obligations are met

---

## Scenario 6: Production Incident Response

### Context
A production outage is detected affecting user transactions.

### Workflow

1. **DevOps Engineer → Developers**
   - **Interaction**: Alert notification and initial triage
   - **Deliverable**: War room or incident channel established

2. **DevOps Engineer → Project Manager**
   - **Interaction**: Incident escalation and impact assessment
   - **Deliverable**: Project Manager activates incident communication plan

3. **Developers ↔ DevOps Engineer**
   - **Interaction**: Debugging using logs and monitoring; implement fix or rollback
   - **Accountability**: DevOps Engineer manages deployment; Developers own fix

4. **Project Manager → Stakeholders**
   - **Interaction**: Incident status updates per communication template
   - **Deliverable**: Regular updates until resolution

5. **DevOps Engineer → Data Analyst**
   - **Interaction**: Request for impact analysis (affected users, transaction volume)
   - **Deliverable**: Data Analyst provides incident impact metrics

6. **Project Manager (Facilitates) → All Involved Parties**
   - **Interaction**: Blameless postmortem to identify root cause and prevention measures
   - **Deliverable**: Postmortem document with action items

7. **Agile Coach (If Needed) → Team**
   - **Interaction**: Facilitate retrospective if incident exposed process or team issues
   - **Deliverable**: Process improvements to prevent similar incidents

---

## Scenario 7: Sprint Planning with Cross-Functional Team

### Context
Beginning of a new sprint with features requiring multiple disciplines.

### Workflow

1. **Product Manager (Presents) → All Team Members**
   - **Handoff**: Prioritized backlog items with acceptance criteria
   - **Interaction**: Product Manager presents sprint goals and success metrics
   - **Deliverable**: Team understands business priorities

2. **UX Designer (Presents) → Developers & QA**
   - **Handoff**: Design specs for features in sprint
   - **Interaction**: Design walkthrough to clarify implementation details
   - **Deliverable**: Team has design context for estimation

3. **Developers → Data Analyst**
   - **Interaction**: Discuss instrumentation needs for sprint features
   - **Deliverable**: Data Analyst adds tracking tasks to sprint backlog

4. **Developers → DevOps Engineer**
   - **Interaction**: Discuss infrastructure or deployment needs
   - **Deliverable**: DevOps Engineer adds infrastructure tasks if needed

5. **QA Engineers → Product Manager & Developers**
   - **Interaction**: Clarify acceptance criteria and testability concerns
   - **Deliverable**: Refined acceptance criteria with test considerations

6. **Legal/Compliance Advisor (If Needed) → Product Manager**
   - **Interaction**: Identify any compliance review needs for sprint items
   - **Deliverable**: Compliance review tasks added to sprint if required

7. **Agile Coach (Facilitates) → Project Manager & Team**
   - **Interaction**: Guide estimation process and team commitment discussion
   - **Deliverable**: Realistic sprint commitment with team buy-in

8. **Project Manager (Documents) → All Team Members**
   - **Handoff**: Sprint plan, capacity allocation, and dependencies documented
   - **Accountability**: Project Manager tracks progress; all team members deliver commitments

---

## Key Collaboration Principles

### Clear Handoffs
- Define what is being handed off (document, artifact, decision)
- Specify when the handoff occurs (milestone, ceremony, ad-hoc)
- Confirm receipt and understanding

### Explicit Accountability
- One role owns the deliverable or decision
- Other roles provide input, review, or approval
- Accountability is documented and visible

### Proactive Communication
- Don't wait for ceremonies; communicate blockers immediately
- Use shared tools (project board, Slack, docs) for transparency
- Follow communication templates for consistency

### Feedback Loops
- Regular checkpoints between dependent roles
- Validate assumptions early and often
- Course-correct based on feedback

---

## How to Use This Document
1. Identify your role in a scenario
2. Understand your handoffs and accountability
3. Proactively reach out to dependent roles
4. Use these patterns as templates for your projects
5. Adapt workflows to your specific project context
