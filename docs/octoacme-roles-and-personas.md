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

## Project Sponsor

### Role Summary
The Project Sponsor champions the project at the executive level, provides strategic direction, secures resources, and is ultimately accountable for overall project success. They remove organizational barriers and ensure the project aligns with business priorities.

### Responsibilities
- Champion the project and secure executive buy-in and budget
- Remove organizational barriers blocking the team's progress
- Approve scope changes, major milestones, and go/no-go decisions
- Provide strategic guidance when the project faces significant risks or pivots
- Represent the project to senior leadership and external stakeholders

### Goals
- Ensure the project delivers measurable business value
- Maintain executive and stakeholder confidence in project direction
- Enable the team to operate with appropriate authority and resources

### Typical Communication
- Monthly or milestone-based briefings with the Project Manager
- Escalation reviews when business-impacting decisions arise
- Participation in project kickoff and major milestone events

### Interactions with Other Roles
- **Project Manager:** Regular status reviews; the PM escalates risks and decisions to the Sponsor for resolution.
- **Change Manager:** Collaborates on organizational communication and alignment strategies.
- **Stakeholders:** Engages stakeholders to secure buy-in and communicate strategic intent.

---

## Change Manager

### Role Summary
The Change Manager leads organizational change initiatives related to the project, supporting adoption, minimizing disruption, and aligning stakeholders throughout the transition. They bridge the gap between project delivery and the humans affected by the change.

### Responsibilities
- Develop and execute a change management plan covering communication, training, and adoption
- Identify impacted stakeholders and assess change readiness
- Facilitate workshops and training sessions to build capability and acceptance
- Track change adoption metrics and report progress to the Project Sponsor and PM
- Address resistance and escalate adoption blockers as needed

### Goals
- Achieve sustainable adoption of new processes or products
- Reduce disruption and organizational resistance to change
- Ensure stakeholders are informed, prepared, and supported

### Typical Communication
- Regular check-ins with the Project Sponsor and Project Manager to align on schedule and risk mitigations
- Stakeholder newsletters and readiness assessments
- Training communications and post-deployment adoption reports

### Interactions with Other Roles
- **Project Sponsor:** Aligns on communication strategy and secures sponsorship for change messaging.
- **Project Manager:** Coordinates change activities with the project schedule and risk register.
- **Subject Matter Expert (SME):** Leverages SME expertise to design effective training and communication content.

---

## Technical Lead

### Role Summary
The Technical Lead bridges the gap between technical and business teams, owns architecture and design decisions, and mentors the engineering team. They serve as the primary escalation point for engineering challenges and ensure technical quality throughout delivery.

### Responsibilities
- Define and own the technical architecture and key design decisions
- Review and approve significant code and infrastructure changes
- Mentor Developers and provide guidance on best practices and standards
- Identify and mitigate technical risks and dependencies
- Collaborate with QA Analyst on testing strategies and acceptance of quality gates

### Goals
- Deliver a technically sound, scalable, and maintainable solution
- Reduce technical debt and surface risks early
- Grow the engineering team's capability and confidence

### Typical Communication
- Daily standups and sprint planning with the development team
- Architecture decision records (ADRs) and technical design documents
- Escalation discussions with the Project Manager when technical blockers arise

### Interactions with Other Roles
- **Developers:** Mentors and guides implementation; reviews and approves pull requests.
- **QA Analyst:** Defines test strategies and validates that quality gates are met before release.
- **Subject Matter Expert (SME):** Engages with SMEs to resolve technical ambiguities in requirements.
- **Project Manager:** Provides technical risk input and effort estimates to inform planning.

---

## QA Analyst

### Role Summary
The QA Analyst defines the testing strategy, ensures product quality, and collaborates with both developers and stakeholders for validation. They are responsible for maintaining quality standards throughout the project lifecycle.

### Responsibilities
- Design and maintain test plans, test cases, and acceptance criteria
- Execute functional, regression, and exploratory tests across iterations
- Document, triage, and track defects through resolution
- Validate bug fixes and ensure no regressions are introduced
- Report test results, quality metrics, and readiness assessments to the Project Manager and Technical Lead

### Goals
- Prevent defects from reaching production
- Ensure delivery meets defined acceptance criteria and quality standards
- Build a reliable, repeatable test suite that accelerates future releases

### Typical Communication
- Sprint-level test summary reports shared with the Project Manager and Technical Lead
- Defect triage sessions with Developers
- Go/no-go quality readiness reports before each release

### Interactions with Other Roles
- **Developers:** Works closely with developers to reproduce issues, clarify acceptance criteria, and verify fixes.
- **Technical Lead:** Aligns on test strategy, quality gates, and release readiness criteria.
- **Project Manager:** Reports test progress and quality risks to inform release planning.
- **Subject Matter Expert (SME):** Consults SMEs to validate domain-specific test scenarios and acceptance criteria.

---

## Subject Matter Expert (SME)

### Role Summary
The Subject Matter Expert contributes deep domain knowledge, reviews requirements, and assists in complex decision-making. SMEs ensure that project outputs meet real-world business and operational needs.

### Responsibilities
- Provide authoritative domain knowledge to inform requirements and design decisions
- Review and validate requirements, user stories, and acceptance criteria for accuracy and completeness
- Participate in workshops, design sessions, and UAT to ensure business alignment
- Identify domain-specific risks, constraints, and edge cases
- Support the Change Manager in developing training and communication content

### Goals
- Ensure project outputs accurately reflect domain requirements and business needs
- Reduce rework caused by misunderstood or incomplete requirements
- Accelerate decision-making by providing timely expert input

### Typical Communication
- Engagement in requirements workshops, backlog refinement sessions, and design reviews
- Review and sign-off on domain-critical acceptance criteria
- Collaboration with the Change Manager on training materials and adoption content

### Interactions with Other Roles
- **Product Manager:** Provides domain expertise to refine the product vision, roadmap, and backlog.
- **Technical Lead:** Clarifies complex domain requirements to guide architecture and design decisions.
- **QA Analyst:** Validates test cases and acceptance criteria against domain standards.
- **Change Manager:** Contributes expertise to training materials and stakeholder communications.

---

## How these personas are used in the exercise
- Use these persona definitions to frame scenarios and sample interactions in the Skills Exercise.
- Each persona can be used as a persona prompt for Copilot Spaces to shape role-specific guidance.
- See [RACI Matrix](octoacme-raci-matrix.md) for a summary of each role's level of involvement across key project activities.

