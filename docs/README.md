# OctoAcme Project Management Docs

## Overview

This documentation collection serves as a centralized resource for OctoAcme's project management processes, practices, and guidelines. These documents provide teams with a comprehensive framework for managing software projects from initiation through delivery and retrospective. Whether you're a new team member getting oriented or an experienced contributor looking for process guidance, this index will help you navigate to the right documentation for your needs.

## Project Management Process Summary

OctoAcme follows a structured, iterative approach to project management that emphasizes customer value, clear ownership, and data-informed decision-making. The project lifecycle consists of five distinct phases: **Initiation**, where teams validate business needs and create a Project One-pager with stakeholder alignment; **Planning**, which transforms approved initiatives into actionable backlogs with prioritized work items, acceptance criteria, and risk identification; **Execution**, featuring daily standups and weekly delivery syncs with a focus on small pull requests and continuous integration; **Release**, which standardizes deployment procedures with comprehensive pre-release checklists and rollback plans; and **Retrospective**, where teams capture learnings and convert them into actionable improvements. Throughout these phases, projects are tracked using GitHub Projects with standardized columns (Backlog, Ready, In Progress, In Review, QA, Done), and all work is tied to clear acceptance criteria and a documented Definition of Done.

The framework defines three core personas with distinct but complementary responsibilities. **Developers** design, build, and test software components while participating in code reviews and technical risk identification. **Product Managers** own the product vision, define success metrics, and prioritize the backlog based on customer and business value. **Project Managers** coordinate delivery activities, manage schedules and risks, facilitate key meetings, and maintain transparency through consistent status reporting. Each project requires named ownership from both a Project Manager and Product Lead, ensuring accountability while fostering psychological safety and encouraging team feedback.

Communication and risk management are central to OctoAcme's approach. Teams maintain a **Risk Register** that tracks identified risks with impact/likelihood assessments, ownership, and mitigation plans, which are reviewed during weekly syncs. Communication follows a cadenced structure: daily 15-minute standups focused on progress and blockers, weekly syncs between PM and Product Manager, twice-weekly delivery team standups, and monthly stakeholder updates. Status updates follow standardized templates covering progress, next steps, risks/blockers, and decisions needed. Escalation paths are clearly defined, flowing from team-level triage through PM to Product Lead and ultimately to sponsors for business-impacting issues, with special protocols for security incidents.

Quality assurance is embedded throughout the development lifecycle with multiple validation layers. Teams implement **unit tests for new logic**, integration tests where applicable, and end-to-end smoke tests for critical flows before releases. All code changes go through automated CI pipelines that run tests, linting, and security scanning before merge. Pull requests must be small (ideally ≤400 lines), include issue links and acceptance criteria, and require at least one approval before merging. Pre-release requirements include passing CI, completed acceptance criteria, drafted release notes, documented rollback plans, and successful staging environment smoke tests. The team tracks velocity, burndown metrics, and success indicators identified in project charters, using dashboards to monitor errors, latency, and usage patterns. This comprehensive quality framework ensures reliable, maintainable deliveries while maintaining high observability and the ability to quickly respond to issues.

## Key Process Documentation Links

- [Project Management Overview](octoacme-project-management-overview.md)
- [Project Initiation Guide](octoacme-project-initiation.md)
- [Project Planning](octoacme-project-planning.md)
- [Execution & Tracking](octoacme-execution-and-tracking.md)
- [Risk Management & Communication](octoacme-risks-and-communication.md)
- [Release & Deployment Guide](octoacme-release-and-deployment.md)
- [Retrospective & Continuous Improvement](octoacme-retrospective-and-continuous-improvement.md)
- [Roles & Personas](octoacme-roles-and-personas.md)
