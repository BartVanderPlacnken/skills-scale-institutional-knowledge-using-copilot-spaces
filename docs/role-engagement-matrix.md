# OctoAcme — Role Engagement Matrix

This matrix defines who is **Responsible**, **Accountable**, **Consulted**, and **Informed** (RACI) for common project activities across all OctoAcme personas.

For a full description of each role, see [OctoAcme Roles and Personas](octoacme-roles-and-personas.md).

---

## How to Use This Matrix

| Code | Meaning |
|------|---------|
| **R** | **Responsible** — does the work |
| **A** | **Accountable** — owns the outcome; final decision authority |
| **C** | **Consulted** — provides input before or during the activity |
| **I** | **Informed** — kept up to date on decisions and progress |

**Rules of thumb:**
- Every activity should have exactly **one A**.
- Limit the number of **C** entries per activity — too many consultees slow progress.
- Default to **I** for roles that need awareness but not active input.
- When in doubt about engagement level, refer to the [Role Engagement Checklists](role-engagement-checklist.md).

---

## RACI Matrix

| Activity | Project Manager | Product Manager | Developer | UX Designer | Security Lead | Customer Support | Data Analyst | QA / Tester |
|----------|:-:|:-:|:-:|:-:|:-:|:-:|:-:|:-:|
| **Initiation** | A | C | I | I | C | I | C | I |
| **Requirements & Discovery** | C | A | C | C | C | C | C | I |
| **Design** | I | C | C | A | C | I | I | I |
| **Implementation** | I | I | A | C | C | I | C | I |
| **Code Review** | I | I | A | I | C | I | I | I |
| **QA / Testing** | C | I | C | C | C | I | I | A |
| **Release & Deployment** | A | C | R | I | C | C | I | C |
| **Post-release Support** | I | C | C | I | C | A | C | I |
| **Incident Response** | A | I | R | I | C | C | I | I |
| **Retrospective** | A | C | C | C | I | C | C | C |

> **Note:** QA / Tester is referenced in the matrix for completeness. This role is not yet detailed in the persona document — add a dedicated section when the team is ready to formalise it.

---

## Common Engagement Patterns

The following examples illustrate how the matrix translates into day-to-day practice.

### High-Risk Feature Development
1. **Security Lead is Consulted** during Requirements & Discovery and Design to assess threat surface early.
2. **Security Lead reviews the PR** (Code Review — Consulted) before merge.
3. **QA** includes security-specific test cases in the test plan.
4. **Customer Support is Informed** at release so they can prepare FAQs and triage scripts.

### Data-Driven Feature Launch
1. **Data Analyst is Consulted** during Requirements & Discovery to define success metrics and instrumentation needs.
2. **Data Analyst reviews** the implementation to confirm analytics events are correctly specified.
3. **Data Analyst shares** post-release adoption dashboards with the Product Manager (Post-release Support — Consulted).

### Incident Response
1. **Project Manager owns** the incident bridge (Accountable) and coordinates communication.
2. **Developer** investigates and remediates (Responsible).
3. **Security Lead** is Consulted if the incident has a security dimension.
4. **Customer Support** coordinates user-facing messaging and monitors ticket volume.
5. A **Retrospective** is scheduled within one week; the Project Manager facilitates and collects input from all Consulted roles.

---

## Cross-links

- [OctoAcme Roles and Personas](octoacme-roles-and-personas.md)
- [Role Engagement Checklists](role-engagement-checklist.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
