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

## QA / Test Engineers

### Role Summary
QA / Test Engineers define and execute the validation strategy so teams can release with confidence and clear quality signals.

### Responsibilities
- Define quality strategy aligned to acceptance criteria and Definition of Done
- Maintain test coverage plans for unit, integration, and end-to-end testing
- Partner with Developers on testability, defect triage, and regression prevention
- Provide release-readiness quality input and recommend go/no-go decisions

### Goals
- Reduce escaped defects and rework
- Improve confidence in release quality
- Keep quality feedback loops fast and actionable

### Typical Communication
- Test plans linked to backlog items
- Defect triage and quality trend updates
- Release readiness updates with clear risk calls

---

## Engineering Managers / Technical Leads

### Role Summary
Engineering Managers / Technical Leads provide technical direction and execution governance to balance delivery speed, quality, and maintainability.

### Responsibilities
- Guide technical design choices and architecture trade-offs
- Support estimation quality and technical risk mitigation
- Coordinate cross-team technical dependencies
- Mentor engineers and maintain healthy engineering practices

### Goals
- Deliver maintainable systems at predictable pace
- Reduce technical risk and delivery surprises
- Improve team effectiveness and technical consistency

### Typical Communication
- Design reviews and architecture decision records
- Scope and feasibility discussions with PM/PdM
- Dependency and risk updates in planning/execution syncs

---

## UX / Product Designers

### Role Summary
UX / Product Designers translate product intent into usable, accessible experiences that teams can implement with low ambiguity.

### Responsibilities
- Define user journeys, interaction flows, and interface expectations
- Produce wireframes/specs with accessibility considerations
- Validate design assumptions with lightweight user feedback
- Partner with engineering to maintain implementation fidelity

### Goals
- Improve usability and adoption outcomes
- Reduce implementation ambiguity and rework
- Ensure inclusive, accessible user experiences

### Typical Communication
- Design specs and annotations linked to backlog items
- Design walkthroughs with Product and Engineering
- Clarifications during build and QA phases

---

## DevOps / Platform Engineers

### Role Summary
DevOps / Platform Engineers enable reliable build, release, deployment, and observability capabilities across delivery teams.

### Responsibilities
- Maintain CI/CD pipelines and environment reliability
- Define deployment safety checks and rollback readiness
- Improve monitoring, alerting, and operational visibility
- Support incident response readiness and post-incident improvements

### Goals
- Increase release reliability and recovery speed
- Reduce deployment risk and manual operational work
- Keep runtime health visible and actionable

### Typical Communication
- Release readiness checks and deployment windows
- Incident and post-incident operational updates
- Pipeline and environment health reporting

---

## Security / Compliance Representatives

### Role Summary
Security / Compliance Representatives ensure security and policy requirements are integrated from planning through release.

### Responsibilities
- Identify security and compliance risks early in planning
- Define required controls, checks, and approval requirements
- Support threat modeling and remediation prioritization
- Advise on compliance-impacting scope or timeline decisions

### Goals
- Reduce security and compliance risk exposure
- Prevent late-stage policy or control surprises
- Improve secure-by-default delivery behavior

### Typical Communication
- Security requirements in planning artifacts
- Risk and remediation updates during execution
- Approval and exception records for release gates

---

## Customer Support / Operations Liaisons

### Role Summary
Customer Support / Operations Liaisons represent production-user feedback and support readiness needs before and after release.

### Responsibilities
- Surface recurring customer pain points and support trends
- Prepare support-readiness artifacts (FAQs, known issues, runbooks)
- Coordinate customer-impact communication during incidents/releases
- Validate post-release support and adoption signals

### Goals
- Reduce customer-impact surprises at launch
- Improve support readiness and response quality
- Feed real-world learning back into planning and prioritization

### Typical Communication
- Support trend summaries for Product and PM
- Release-support readiness check-ins
- Post-release customer-impact and ticket-theme updates

---

## Cross-role interaction guidance

Use the guidance below to reduce ambiguity at common delivery handoffs:

- **Planning handoff (PdM + PM + Tech Lead + UX + QA):**
  - Confirm scope, acceptance criteria, risks, and non-functional requirements.
  - Assign a named owner for each dependency and risk item.
- **Build handoff (Developers + QA + Tech Lead):**
  - Confirm implementation approach, test strategy, and definition of done.
  - Track open defects and unresolved technical decisions in one shared location.
- **Release handoff (PM + DevOps + QA + Security + Support):**
  - Confirm deployment plan, rollback plan, quality/security checks, and support readiness.
  - Document go/no-go decision with owner and timestamp.
- **Post-release handoff (Support + PdM + PM + Developers):**
  - Share customer-impact signals, incidents, and follow-up actions.
  - Convert learnings into backlog items with owners and due dates.

## Role interaction quick map

- **Developers** collaborate most closely with QA, Tech Leads, UX, and DevOps during execution.
- **Product Managers** align outcomes and priorities with UX, PMs, Support, and Security constraints.
- **Project Managers** coordinate dependencies and decision gates across all roles.
- **QA / Test Engineers** provide release quality signal to PM, Developers, and Product Managers.
- **DevOps / Platform Engineers** partner with PM, Developers, QA, and Security on release safety.
- **Security / Compliance Representatives** advise Product, PM, DevOps, and Developers on required controls.
- **Customer Support / Operations Liaisons** connect production feedback back to Product and delivery teams.

## Why this expanded persona model improves outcomes

- Clarifies ownership, reducing decision latency and missed handoffs.
- Reduces execution risk by defining quality, security, and operations responsibilities earlier.
- Improves onboarding by giving new contributors clear role boundaries and collaboration patterns.
- Increases delivery predictability through explicit, cross-functional interaction guidance.

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
