# OctoAcme — Role Engagement Checklists

Use these checklists to verify that the right personas are involved at the right time. They complement the [Role Engagement Matrix](role-engagement-matrix.md) and should be completed as part of the corresponding lifecycle stage.

For role descriptions, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

---

## Initiation Checklist

Complete this checklist when a new project idea or feature proposal is ready to be explored. Reference the [Project Initiation Guide](octoacme-project-initiation.md) for the full initiation process.

- [ ] **Stakeholders identified** — primary stakeholders listed in the project one-pager, including Product Manager, Project Manager, and any relevant business owners.
- [ ] **UX Designer engaged** — if the initiative has significant user-facing changes, a UX Designer has been assigned or consulted.
- [ ] **Data Analyst consulted** — success metrics and required instrumentation have been discussed; a Data Analyst has confirmed how outcomes will be measured.
- [ ] **Security constraints reviewed** — Security Lead has been made aware of the initiative; any known compliance, data-privacy, or risk constraints are documented.
- [ ] **Customer Support informed** — Customer Support is aware of the initiative and has flagged any existing user-pain-point data that should influence scope.
- [ ] **Role-engagement matrix reviewed** — the team has used the [Role Engagement Matrix](role-engagement-matrix.md) to confirm who should be Responsible, Accountable, Consulted, or Informed during delivery.
- [ ] **"Proposed team / roles" section populated** in the project one-pager, informed by the matrix.

---

## Pre-release Checklist

Complete this checklist before every production release. Reference the [Release & Deployment guide](octoacme-release-and-deployment.md) for the full release process.

- [ ] **Security review complete** — Security Lead has reviewed or signed off on any high-risk changes included in this release.
- [ ] **QA sign-off obtained** — QA / Tester has completed testing against acceptance criteria and the Definition of Done.
- [ ] **UX fidelity verified** — UX Designer has reviewed implemented UI changes and approved for release (or accepted known deviations).
- [ ] **Release notes drafted** — Release notes are complete, accurate, and available for Customer Support to use.
- [ ] **Support readiness confirmed** — Customer Support has reviewed the release notes, prepared FAQs or triage scripts, and confirmed readiness to handle user questions.
- [ ] **Analytics tracking validated** — Data Analyst has confirmed that new instrumentation events fire correctly in the staging/pre-production environment.
- [ ] **Documentation updated** — All relevant user-facing and internal documentation has been updated to reflect new or changed behaviour.
- [ ] **Go/no-go decision recorded** — Project Manager has facilitated a go/no-go call; outcome and attendees are recorded.

---

## Incident Readiness Checklist

Verify incident readiness at the start of each release cycle or quarterly, and immediately before high-risk releases.

- [ ] **On-call rotation defined** — Developer on-call schedule is published and all team members know the current rotation.
- [ ] **Escalation path documented** — The sequence for escalating an incident (Developer → Project Manager → Product Manager → Leadership) is documented and accessible.
- [ ] **Security Lead available** — Security Lead (or a named backup) is reachable during the release window in case of a security-related incident.
- [ ] **Customer Support notified** — Customer Support knows the release is happening and has a contact for real-time updates during incidents.
- [ ] **Stakeholder notification plan ready** — Project Manager has a template or runbook for notifying stakeholders of a major incident, including timing and channel.
- [ ] **Rollback plan documented** — Developers have a tested rollback or feature-flag strategy for the release.
- [ ] **Post-incident retrospective owner assigned** — A named owner (typically the Project Manager) is responsible for scheduling and facilitating a post-incident retrospective within five business days of any severity-1 or severity-2 incident.

---

## Cross-links

- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [Role Engagement Matrix](role-engagement-matrix.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Release & Deployment](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
