# Course 07 — AI for App Building
## AI-Assisted IT Support Management System Development, Debugging & Testing

### Course Overview
This course focused on using AI to support application development, improve existing code, identify software defects, and test application behavior through practical exercises.

## Task 13: AI-Assisted IT Support Management System Development & Browser Testing

**Objective:** Develop and test a browser-based IT Support Management System with AI assistance.

**Practical Scenario:** Building a single-page IT support application for managing support tickets, staff information, and department reports.

**Technology Stack:**
- HTML5.
- Tailwind CSS.
- Vanilla JavaScript.
- Browser localStorage for client-side data persistence.

**Work Completed:**
- Developed an IT Support Management System prototype.
- Created a dashboard with ticket summary indicators.
- Added ticket management functionality.
- Included staff and workload information.
- Developed reporting and CSV export features.
- Implemented ticket creation, status updates, deletion, searching, and filtering.
- Used localStorage to retain application data between page refreshes.
- Tested the application through browser-based checks.
- Corrected a ticket priority normalization issue affecting the Critical filter.

**Testing Results:**

<text>9 of 9 reported browser checks passed.</text>

The checks covered:
1. Ticket creation.
2. Ticket status updates.
3. Dashboard KPI refresh.
4. Ticket search.
5. Critical-priority filtering.
6. Staff and workload display.
7. Reports and CSV export.
8. Data persistence after refreshing the browser.
9. Ticket deletion.

**Quality and Technical Review:**
The application is a frontend prototype. It does not provide production-grade authentication, a backend database, or multi-user synchronization. Browser localStorage is suitable for a demonstration but should not be treated as secure enterprise data storage.

**Skills Demonstrated:** AI-assisted application development, HTML, CSS, JavaScript, debugging, browser testing, UI functionality, and data handling.

## Task 14: AI-Assisted Python Code Debugging & Software Testing

**Objective:** Use AI to identify programming errors, improve Python code, and evaluate application behavior across different test scenarios.

**Practical Scenario:** Debugging a Python IT support ticket reporting program that calculates the number and percentage of resolved tickets.

**Work Completed:**
- Reviewed the original Python code.
- Identified a type-related error involving a string-based counter and numeric calculation.
- Identified a division-by-zero risk when the ticket list is empty.
- Improved the logic by initializing the resolved counter as an integer.
- Added a condition to handle an empty ticket list.
- Improved percentage formatting.
- Prepared five test scenarios:
  1. Normal mixed ticket results: 4 tickets, 2 resolved, 50%.
  2. All tickets resolved.
  3. No tickets resolved.
  4. Empty ticket list.
  5. A single resolved ticket.

**Quality and Testing Review:**
The corrected logic was reviewed against the expected results for all five scenarios. Gemini reported execution and verification; the code logic was also independently reviewed. These expected results should not be confused with a separately documented live test execution.

**Skills Demonstrated:** Python programming, code debugging, error identification, defensive programming, test-case design, and AI-assisted software quality review.

## Tools and Methodology

**AI Tool:** Google Gemini

**Development and Testing Tools:** Browser environment and Python-compatible code editor.

**Workflow:**
1. Define the application or programming task.
2. Generate or review the initial code.
3. Identify errors and functional weaknesses.
4. Request AI-assisted corrections.
5. Review the proposed code changes.
6. Test expected behavior across different scenarios.
7. Document limitations and final results.

## Learning Outcomes

- Understand how AI can support application development.
- Develop a basic browser-based management application.
- Work with HTML, CSS, and JavaScript.
- Use browser testing to evaluate application features.
- Identify and correct common Python errors.
- Handle empty data and invalid calculation conditions.
- Design practical test cases.
- Review AI-generated code critically.

## Project Status

**Completed: 2 of 2 practical tasks**

Both tasks were completed as AI-assisted application development and software testing exercises. The IT Support Management System is a frontend prototype, and the Python debugging task is a learning exercise rather than a production software release.

---

*Prepared as part of the Google AI Professional Certificate — Practical Portfolio.*
