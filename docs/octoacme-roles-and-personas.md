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
UX Designers craft intuitive, accessible user experiences. They translate product requirements into user flows, wireframes, and high-fidelity designs, and validate that implemented features meet usability expectations.

### Responsibilities
- Design user flows, wireframes, and prototypes
- Conduct usability reviews and gather user feedback
- Collaborate with Product Managers on requirements and acceptance criteria
- Review implemented features for UX fidelity before release
- Maintain a design system and ensure visual consistency

### Goals
- Deliver experiences that are intuitive, accessible, and delightful
- Reduce usability defects found post-release
- Build a shared design language across products

### Typical Communication
- Design reviews with Product Managers and Developers (bi-weekly or per feature)
- Async design handoff via Figma/design tool comments
- User research readouts shared with the broader team

### Interactions with Existing Roles
- **Product Managers:** Collaborate during discovery and requirements to align user needs with business goals; jointly refine acceptance criteria.
- **Developers:** Provide design specs and assets; review implemented UI for fidelity; clarify design intent during implementation.
- **Project Managers:** Flag design dependencies and blockers; participate in kickoff and sprint planning.
- **QA / Testers:** Define usability acceptance criteria; validate accessibility and interaction quality.

---

## Security Lead

### Role Summary
Security Leads identify, assess, and mitigate security risks across the product lifecycle. They advise teams on secure design, review code and architecture for vulnerabilities, and coordinate incident response from a security perspective.

### Responsibilities
- Conduct threat modelling and risk assessments for new features and architectural changes
- Review code and architecture for security vulnerabilities
- Define and enforce security standards and best practices
- Advise on compliance, data protection, and access controls
- Lead or participate in security incident investigations

### Goals
- Reduce the attack surface and eliminate known vulnerabilities before release
- Build a security-conscious engineering culture
- Ensure compliance with relevant security standards and regulations

### Typical Communication
- Asynchronous review comments on PRs and design docs for high-risk features
- Security-focused check-ins during sprint planning for high-risk work
- Incident bridges and post-incident reviews as needed

### Interactions with Existing Roles
- **Developers:** Provide security guidance during implementation; review high-risk PRs; pair on remediations.
- **Product Managers:** Assess security implications of new features; flag regulatory constraints that affect scope.
- **Project Managers:** Communicate security review timelines; escalate unresolved risks.
- **QA / Testers:** Define security test cases and penetration test scope; validate remediations.

---

## Customer Support

### Role Summary
Customer Support representatives are the voice of the user inside the team. They surface recurring user pain points, facilitate incident triage from a customer-impact perspective, and ensure readiness materials are in place before release.

### Responsibilities
- Collect, triage, and escalate user-reported issues and feedback
- Validate that release notes, FAQs, and help content are accurate and complete
- Contribute to incident response by communicating customer impact and coordinating user-facing messaging
- Monitor support trends and share insights with Product and Engineering

### Goals
- Reduce user-facing errors and time-to-resolution for support tickets
- Ensure users have clear guidance and self-service resources at launch
- Strengthen the feedback loop between users and the product team

### Typical Communication
- Weekly support trend summaries shared with Product Managers
- Pre-release readiness reviews (joins release go/no-go calls)
- Incident communication channels (Slack, email) during live incidents

### Interactions with Existing Roles
- **Product Managers:** Provide qualitative user feedback and ticket data to inform prioritization; validate feature readiness.
- **Developers:** Report reproducible bugs; validate fixes from a user perspective.
- **Project Managers:** Participate in release readiness reviews; flag support-readiness risks.
- **Security Lead:** Coordinate user-facing communications during security incidents.

---

## Data Analyst

### Role Summary
Data Analysts develop dashboards and metrics frameworks, analyse product usage data, and surface insights that guide prioritisation and measure outcomes.

### Responsibilities
- Define and track key product metrics and KPIs
- Build and maintain dashboards for product, engineering, and leadership
- Analyse feature adoption, performance, and user behaviour
- Partner with Product Managers on hypothesis definition and experiment design
- Provide data-driven input to retrospectives and planning

### Goals
- Make product decisions faster and more confident through reliable data
- Reduce time from question to insight
- Ensure analytic instrumentation is in place before features ship

### Typical Communication
- Sprint or bi-weekly data review sessions with Product Managers
- Dashboard links shared in project channels for self-service insight
- Async comments and data pull requests for metric definitions

### Interactions with Existing Roles
- **Product Managers:** Collaborate on success metrics and experiment design; deliver insights that validate or challenge assumptions.
- **Developers:** Specify instrumentation requirements (events, properties) during implementation; validate tracking is correct.
- **Project Managers:** Report on project health metrics; flag data-quality issues that could mask progress.
- **QA / Testers:** Validate that analytics events fire correctly in test environments.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- When identifying roles for a new initiative, refer to the [Role Engagement Matrix](role-engagement-matrix.md) to determine who should be Responsible, Accountable, Consulted, or Informed at each lifecycle stage.
- Use the [Role Engagement Checklists](role-engagement-checklist.md) to verify that the right personas are involved at initiation, pre-release, and during incidents.

