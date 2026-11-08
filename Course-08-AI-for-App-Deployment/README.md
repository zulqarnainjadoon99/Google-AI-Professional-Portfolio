# Course 08 — AI for App Deployment
## AI-Assisted Web Application Deployment, Monitoring & Maintenance

### Course Overview
This course focused on planning web application deployment, understanding hosting options, troubleshooting common application issues, and preparing monitoring and maintenance procedures for reliable application operation.

## Task 15: AI-Assisted Web Application Deployment Strategy & DevOps Planning

**Objective:** Use AI to develop a practical deployment strategy for a web-based IT Support Management System.

**Practical Scenario:** Preparing a deployment plan for the IT Support Management System using modern web hosting platforms.

**Work Completed:**
- Reviewed the application structure and deployment requirements.
- Compared GitHub Pages, Netlify, and Cloudflare Pages.
- Selected Netlify as the proposed deployment platform for the exercise.
- Prepared a GitHub-connected deployment workflow.
- Documented the proposed repository structure:
  - `index.html`
  - `README.md`
  - `LICENSE`
- Reviewed deployment configuration and common hosting errors.
- Documented basic security considerations.
- Reviewed browser localStorage limitations.
- Identified future development requirements, including:
  - Backend services.
  - Database integration.
  - User authentication.
  - Multi-user synchronization.
  - Real-time communication using WebSockets.

**Quality and Deployment Review:**
This task produced a deployment strategy and technical guide. It does not claim that the application was actually deployed to a live hosting platform. For a simple static application in the repository root, Netlify's publish directory can be set to `.` and the build command left blank when no build process is required. Private browsing storage behavior varies by browser and session. HTTPS protects data in transit but does not encrypt localStorage contents.

**Skills Demonstrated:** Deployment planning, hosting platform comparison, GitHub workflow understanding, DevOps fundamentals, web application architecture, and technical documentation.

## Task 16: AI-Assisted Application Monitoring, Troubleshooting & Maintenance Plan

**Objective:** Develop a structured monitoring, troubleshooting, and maintenance plan for an IT support web application.

**Practical Scenario:** Preparing an operational monitoring and maintenance guide for the IT Support Management System.

**Work Completed:**
- Identified frontend and backend monitoring considerations.
- Reviewed proposed uptime and performance indicators.
- Documented browser Developer Tools:
  - Console for JavaScript errors and warnings.
  - Network for requests and responses.
  - Application for browser storage inspection.
- Prepared troubleshooting scenarios for:
  - Website 404 errors.
  - Tailwind CSS CDN loading issues.
  - JavaScript errors.
  - localStorage persistence problems.
  - CSV export failures.
- Developed an incident response approach.
- Reviewed deployment rollback options through Netlify and Git.
- Documented localStorage data backup considerations.
- Prepared proposed weekly and monthly maintenance activities.
- Included security and operational readiness considerations.
- Created a simulated incident record: `INC-REP-9041`.

**Quality and Monitoring Review:**
The 99.9% uptime figure is a proposed target, not a measured result. HTTP status codes must be interpreted in context because redirects and other valid responses do not automatically indicate an outage. A JavaScript error does not necessarily stop every event listener or feature. Exporting only ticket records is not a complete backup if staff, audit history, and settings are also important. Monitoring targets and incident procedures should be validated in an actual deployment environment.

**Skills Demonstrated:** Application monitoring, troubleshooting, incident response, maintenance planning, deployment rollback awareness, data backup planning, and operational documentation.

## Tools and Methodology

**AI Tool:** Google Gemini

**Development and Deployment Concepts:** GitHub, Netlify, browser Developer Tools, HTML, JavaScript, and localStorage.

**Workflow:**
1. Review application architecture and deployment needs.
2. Compare hosting and deployment options.
3. Prepare a deployment strategy.
4. Identify monitoring indicators.
5. Develop troubleshooting scenarios.
6. Prepare incident response and maintenance procedures.
7. Review operational risks and technical limitations.

## Learning Outcomes

- Understand basic web application deployment concepts.
- Compare modern static hosting platforms.
- Understand GitHub-connected deployment workflows.
- Identify common web application errors.
- Use browser Developer Tools for troubleshooting.
- Plan application monitoring and maintenance.
- Understand rollback and backup considerations.
- Prepare structured operational incident documentation.

## Project Status

**Completed: 2 of 2 practical tasks**

Both tasks were completed as AI-assisted deployment planning and application operations documentation exercises. The deployment strategy and monitoring plan are portfolio deliverables, not evidence of a live production deployment or measured service-level performance.

---

*Prepared as part of the Google AI Professional Certificate — Practical Portfolio.*
