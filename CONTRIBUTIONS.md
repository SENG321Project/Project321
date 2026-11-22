# Team Members Individual Contributions

---

## Sprint 1 – Individual Contributions

This section details the individual contributions of each team member for Sprint 1 of the **CampusEvent** software engineering project. It provides full traceability for assigned roles, tasks, issues, pull requests, commits, and deliverables in accordance with SENG 321 course requirements.

### 1. Fırat Haki Beyhansoy
* **Student ID:** 240201062
* **GitHub Username:** @firathaki55
* **Project Role:** Scrum Master & Agile Process Coach

**Key Contributions & Responsibilities:**
* Facilitated Sprint 1 planning, backlog organization, and team task assignments.
* Authored Team Roles and RACI Matrix documentation to establish team accountability.
* Enforced Git-Flow branching strategies (`main`, `develop`, `feature/*`) and branch protection rules.
* Managed merge conflict resolution and consolidated the master `CONTRIBUTIONS.md` file.
* Conducted peer code reviews, provided feedback, and approved Pull Requests to ensure repository standards.

**Traceability & Verification Links:**
* **Issue:** #1 - Team Roles & RACI Matrix
* **Pull Request:** #7 - Merge RACI Matrix and Team Roles into develop
* **Commit:** `48812f8` - Add RACI matrix and team roles
* **Deliverable File(s):** `teamrolesandRACİ.md`, `CONTRIBUTIONS.md`

---

### 2. Melisa Dalkıran
* **Student ID:** 230205028
* **GitHub Username:** @melisadlk
* **Project Role:** Product Owner & Developer

**Key Contributions & Responsibilities:**
* Defined project scope, problem statement, key stakeholders, and high-level requirements for the Project Proposal.
* Authored and structured the official Project Proposal documentation (`CampusEvent_Project_Proposal_.pdf`).
* Configured feature branch (`feature/project-proposal`) adhering to Git-Flow guidelines.
* Created and managed task tracking for the proposal creation workflow.
* Opened Pull Request #9 targeting `develop`, refined PR descriptions, and coordinated peer reviews.

**Traceability & Verification Links:**
* **Issue:** #2 - Project Proposal Creation
* **Pull Request:** #9 - Merge Project Proposal into develop
* **Commit:** `8588269` - Add Project Proposal
* **Deliverable File(s):** `CampusEvent_Project_Proposal_.pdf`

---

### 3. Simge Kahveci
* **Student ID:** 230204030
* **GitHub Username:** @SimgeKahveci
* **Project Role:** System Analyst & Requirement Specialist

**Key Contributions & Responsibilities:**
* Defined system purpose, target users, and stakeholders for System Vision and Boundary specifications.
* Established system responsibilities, core functionalities, and boundaries for the CampusEvent platform.
* Outlined in-scope and out-of-scope features, constraints, and assumptions aligned with the project proposal.
* Created and structured the System Vision and Boundary document (`system_vision_and_boundary.pdf`).
* Managed feature branch (`feature/system-vision`) and conducted peer review coordination.

**Traceability & Verification Links:**
* **Issue:** #4 - System Vision and Boundary Specification
* **Pull Request:** #8 - Merge System Vision into develop
* **Commit:** `ad70760` - Implementation & Integration Engineer
* **Deliverable File(s):** `system_vision_and_boundary.pdf`

---

### 4. Elif Uyanık
* **Student ID:** 240201302
* **GitHub Username:** @elifuyanik06
* **Project Role:** Software Architect & API Designer

**Key Contributions & Responsibilities:**
* Created the initial OpenAPI 3.1.0 specification for the CampusEvent platform.
* Designed RESTful API endpoints for authentication, event management, event registration, QR ticketing, ticket verification, and attendance tracking.
* Defined HTTP methods, request parameters, request bodies, and response structures for API operations.
* Prepared reusable data schemas for users, events, registrations, tickets, and attendance records using JWT Bearer Authentication.
* Documented HTTP status codes (`200`, `201`, `400`, `401`, `403`, `404`, `409`) and validated specs using Swagger Editor.

**Traceability & Verification Links:**
* **Issue:** #3 - OpenAPI Specification Draft
* **Pull Request:** #14 - Merge OpenAPI Specification into develop
* **Commit:** `749eef2` - openapi draft
* **Deliverable File(s):** `api/openapi.yaml`

---

### 5. Rumeysa Kurucan
* **Student ID:** 230205062
* **GitHub Username:** @RumeysaKrcn
* **Project Role:** DevOps & Infrastructure Engineer

**Key Contributions & Responsibilities:**
* Established the GitHub Organization account to centralize all project repositories and team assets.
* Onboarded team members, teaching assistants, and the course instructor with appropriate permissions.
* Configured access control levels (Admin, Write, Read) and set up Branch Protection Rules for `main` and `develop`.
* Restricted direct code pushes to core branches, enforcing mandatory PR workflows and code reviews.
* Authored the Git-Flow guidelines documentation (`GIT_FLOW.md`).

**Traceability & Verification Links:**
* **Issue:** #5 - DevOps & Repository Setup
* **Pull Request:** #13 - Merge Git-Flow Configuration into develop
* **Commit:** `cbc04dd` - Set up Git-Flow
* **Deliverable File(s):** `GIT_FLOW.md`

---

### 6. Umut Sanem Akbayır
* **Student ID:** 230201061
* **GitHub Username:** @akbayirsanem21-sys
* **Project Role:** QA & Test Automation Engineer

**Key Contributions & Responsibilities:**
* Authored and structured the Initial Product Backlog and QA Test Planning documentation (`CampusEvent_Backlog.pdf`).
* Defined prioritized epics, features, and 10 user stories with detailed acceptance criteria and story point estimations.
* Developed initial QA test strategy including unit, integration, and end-to-end testing approaches.
* Prepared 16 test scenarios covering authentication, event management, registration, QR ticketing, and attendance tracking.
* Formulated defect tracking procedures, test coverage goals, Definition of Ready (DoR), and Definition of Done (DoD).

**Traceability & Verification Links:**
* **Issue:** #6 - Initial Product Backlog & QA Test Planning
* **Pull Request:** #12 - Merge Product Backlog and QA Strategy into develop
* **Commit:** `7494bda` - Initial Product Backlog
* **Deliverable File(s):** `CampusEvent_Backlog.pdf`

---
---

## Sprint 2 – Individual Contributions

This section outlines the individual contributions of each team member for Sprint 2 of the **CampusEvent** software engineering project, maintaining end-to-end traceability across issues, branches, pull requests, automated CI checks, and sprint deliverables.

### 1. Fırat Haki Beyhansoy
* **Student ID:** 240201062
* **GitHub Username:** @firathaki55
* **Project Role:** Scrum Master & DevOps Lead

**Key Contributions & Responsibilities:**
* Implemented the GitHub Actions CI/CD workflow (`.github/workflows/ci.yml`) on `develop` to automatically validate Sprint 2 deliverables on every Pull Request.
* Set up and managed the Sprint 2 Kanban Project board, created and assigned Sprint 2 tracking issues, and configured project workflow rules.
* Enforced Git-Flow branching (`main`, `develop`, `feature/*`) and branch protection policies, resolving branch targeting and PR workflow issues across the team.
* Authored the Sprint 2 Scrum Master coordination report (`Sprint2_Coordination_Report.md`).
* Reviewed, approved, and merged all team feature Pull Requests into `develop`, consolidated `CONTRIBUTIONS.md`, and managed the final `develop` -> `main` merge and `v2.0.0` release.

**Traceability & Verification Links:**
* **Issue:** #22 and #19   - Sprint 2 Coordination, CI/CD Setup & Release Management
* **Pull Request:** #25 and #26 (CI Workflow), #<Coordination_PR_No> (Coordination Report), #<Contributions_PR_No> (Update CONTRIBUTIONS.md)
* **Deliverable File(s):** `.github/workflows/ci.yml`, `Sprint2_Coordination_Report.md`, `CONTRIBUTIONS.md`

---

### 2. Melisa Dalkıran
* **Student ID:** 230205028
* **GitHub Username:** @melisadlk
* **Project Role:** Product Owner

**Key Contributions & Responsibilities:**
* Defined the project vision, goals, target user needs, scope, and acceptance criteria for the Sprint 2 requirements baseline.
* Authored and structured the official Software Requirements Specification (`CampusEvent_SRS.pdf`) covering system purpose, scope, and user roles.
* Organized and documented 36 functional requirements (`FR-01` to `FR-36`), system interfaces, data requirements, use cases, and acceptance conditions.
* Created the `feature/srs-document` branch from `develop` and submitted Pull Request #27 for peer review and integration.

**Traceability & Verification Links:**
* **Issue:** #18 - Software Requirements Specification (SRS)
* **Pull Request:** #27 - Add CampusEvent SRS document
* **Deliverable File(s):** `CampusEvent_SRS.pdf`

---

### 3. Simge Kahveci
* **Student ID:** 230204030
* **GitHub Username:** @SimgeKahveci
* **Project Role:** Implementation & Integration Engineer

**Key Contributions & Responsibilities:**
* Prepared UI/UX prototype specifications and screen flows for student, organizer, and administrator journeys aligned with the SRS.
* Created end-to-end user flow diagrams covering registration, event discovery, ticketing, QR verification, and attendance workflows.
* Ensured consistency across UI/UX deliverables, functional requirements, and Sprint 2 quality expectations.
* Worked on the `feature/user-flow-diagrams` branch following Git-Flow guidelines and coordinated peer reviews.

**Traceability & Verification Links:**
* **Issue:** #24 - Sprint 2 UI/UX & User Flow Diagrams
* **Pull Request:** #31 - Add user flow diagrams and UI/UX specification
* **Deliverable File(s):** `uiux_user_flow_specification.pdf`

---

### 4. Elif Uyanık
* **Student ID:** 240201302
* **GitHub Username:** @elifuyanik06
* **Project Role:** Software Architect – C4 & UML Diagrams

**Key Contributions & Responsibilities:**
* Designed the C4 Level 1 (System Context), C4 Level 2 (Container), and C4 Level 3 (Component) architectural diagrams for the CampusEvent platform.
* Created the UML Use Case Diagram and UML Class Diagram defining system entities, relationships, and user role interactions.
* Designed UML Sequence Diagrams for Event Registration & Ticket Generation and QR Verification & Attendance workflows.
* Reviewed, refined, and compiled all seven architectural diagrams into a unified PDF deliverable (`CampusEvent_Sprint2_C4_UML_Diagrams.pdf`) aligned with the SRS and Refined Backlog.

**Traceability & Verification Links:**
* **Issue:** #20 - C4 & UML Architectural Diagrams
* **Pull Request:** #32 - Add C4 and UML diagrams
* **Deliverable File(s):** `CampusEvent_Sprint2_C4_UML_Diagrams.pdf`

---

### 5. Rumeysa Kurucan
* **Student ID:** 230205062
* **GitHub Username:** @RumeysaKrcn
* **Project Role:** UI/UX Designer & DevOps Engineer

**Key Contributions & Responsibilities:**
* Designed core user interface screens (Login, Events Feed, Event Details, Create Event, and My Events) and interactive user navigation flows in Figma.
* Prepared the `CampusEvent_Figma_Prototypes.pdf` deliverable containing the accessible Figma prototype link and annotated screen captures.
* Created the `feature/figma-prototypes` branch from `develop`, uploaded the deliverable, and opened Pull Request #28 targeting `develop`.
* Reviewed and approved Pull Requests submitted by teammates to support repository quality and integration workflows.

**Traceability & Verification Links:**
* **Issue:** #23 - UI/UX Prototype Design
* **Pull Request:** #28 - Add interactive UI/UX Figma prototypes
* **Deliverable File(s):** `CampusEvent_Figma_Prototypes.pdf`

---

### 6. Umut Sanem Akbayır
* **Student ID:** 230201061
* **GitHub Username:** @akbayirsanem21-sys
* **Project Role:** QA & Test Automation Engineer

**Key Contributions & Responsibilities:**
* Authored and structured the Refined Product Backlog (`CampusEvent_Sprint2_Refined_Product_Backlog.pdf`) and Non-Functional Requirements & QA Test Plan (`CampusEvent_Sprint2_NFR_Quality_QA_Test_Plan.pdf`).
* Refined 18 user stories with priorities, acceptance criteria, dependencies, proposed owners, and story point estimates totaling 80 SP.
* Defined 15 non-functional requirements covering performance, security, usability, and reliability, establishing measurable quality criteria aligned with the SRS.
* Prepared 25 functional test scenarios and 6 non-functional verification scenarios with expected results linked to functional requirements.
* Created the `feature/sprint2-qa-backlog` branch and opened Pull Request #29 targeting `develop` linked to Issue #21.

**Traceability & Verification Links:**
* **Issue:** #21 - Define NFR, Quality Measures, Test Plan & Update Product Backlog
* **Pull Request:** #29 - Sprint 2 Refined Backlog, NFR and QA Test Plan
* **Deliverable File(s):** `CampusEvent_Sprint2_Refined_Product_Backlog.pdf`, `CampusEvent_Sprint2_NFR_Quality_QA_Test_Plan.pdf`
