# Sprint 2 Coordination & Progress Report — CampusEvent

**Course:** SENG 321 – Software Engineering Project  
**Project:** CampusEvent (Campus Event Management & QR Ticketing System)  
**Sprint:** Sprint 2 — Requirements Specification, UI/UX Prototyping & Software Architecture  
**Scrum Master & DevOps Lead:** Fırat Haki Beyhansoy  

---

## 1. Sprint 2 Objectives
Sprint 2 focuses on translating the initial project vision and system boundaries established in Sprint 1 into detailed engineering artifacts. Specifically, the team targeted four core deliverables:
1. Detailed Software Requirements Specification (SRS) and refined Product Backlog.
2. Non-Functional Requirements (NFR), quality measures, and test scenarios.
3. Interactive UI/UX prototypes in Figma along with end-to-end User Flow diagrams.
4. Comprehensive Software Architecture documentation including C4 models and UML diagrams.

---

## 2. Team Roles & Task Distribution
To ensure balanced workload distribution and verifiable individual contributions (commits and Pull Requests) across all six team members, Sprint 2 tasks were structured and tracked via GitHub Issues and the Sprint 2 Project Board:

| Team Member | Role | Assigned Deliverables & Target Files | Branch |
| :--- | :--- | :--- | :--- |
| **Melisa** | Product Owner / Requirements Lead | Detailed Software Requirements Specification (`CampusEvent_SRS.pdf`) | `feature/srs-document` |
| **Fırat Haki Beyhansoy** | Scrum Master & DevOps Lead | Sprint 2 Coordination Report (`Sprint2_Coordination_Report.md`), CI Workflow (`.github/workflows/ci.yml`), `CONTRIBUTIONS.md` & `v2.0.0` Release | `feature/ci-workflow`, `feature/coordination-report` |
| **Elif Uyanık** | Lead Software Architect | Software Architecture Documentation, C4 Models & UML Diagrams (`CampusEvent_Architecture_C4_UML.pdf`) | `feature/architecture-c4-uml` |
| **Umut Sanem Akbayır** | QA & Test Automation Engineer | Non-Functional Requirements, Quality Measures, Test Plan (`CampusEvent_NFR_and_TestPlan.pdf`) & Refined Backlog (`CampusEvent_Backlog.pdf`) | `feature/nfr-and-backlog` |
| **Rümeysa Kurucan** | UI/UX Prototyping Lead | Figma Interactive UI/UX Prototypes for Student & Organizer Flows (`CampusEvent_Figma_Prototypes.pdf`) | `feature/figma-prototypes` |
| **Simge Kahveci** | User Flow & Integration Engineer | End-to-End User Flow Diagrams & Requirements Alignment (`CampusEvent_User_Flow_Diagrams.pdf`) | `feature/user-flow-diagrams` |

---

## 3. Process Management & DevOps Governance
* **GitHub Project Board & Issue Tracking:** All Sprint 2 work items were broken down into dedicated GitHub Issues linked to the Sprint 2 Kanban board (`To Do`, `In Progress`, `Done`) for transparent progress monitoring.
* **Git-Flow & Branch Protection:** Direct pushes to `main` and `develop` remain restricted. Every member develops on an isolated `feature/*` branch created from `develop` and submits a Pull Request requiring at least one peer/Scrum Master review before merging.
* **Continuous Integration (CI):** A GitHub Actions workflow (`.github/workflows/ci.yml`) was implemented on `develop` and `main` to automatically verify core repository files (`CONTRIBUTIONS.md`, `openapi.yaml`, `git-flow-setup`) and ensure all `.md` and `.pdf` deliverables are non-empty upon every Pull Request.

---

## 4. Coordination Decisions & Risk Mitigation
* **Splitting Deliverable 3 for Parallel Execution:** UI/UX prototyping and User Flow modeling were separated into two distinct Issues and target files (`CampusEvent_Figma_Prototypes.pdf` and `CampusEvent_User_Flow_Diagrams.pdf`) so both contributors can work concurrently without merge conflicts while maintaining clear individual PR records.
* **Consistent Root-Level Naming Convention:** Following the repository structure established in Sprint 1, all team deliverables follow a standardized `CampusEvent_<Artifact>.pdf` naming convention in the repository root for straightforward review and release packaging.
* **Cross-Artifact Traceability:** Functional requirements in the SRS, acceptance criteria in the refined Product Backlog, Figma screens, and C4/UML architectural views were aligned around the core CampusEvent modules (Authentication, Event Management, Registration, QR Ticket Generation & Check-In).
