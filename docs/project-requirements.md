# Project Requirements Document

## 1. Project Name
Cloud Cost & Project Resource Planner

## 2. Project Purpose
To provide a simple tool for estimating cloud costs and planning project budgets before implementation.

## 3. Target Users
- Project managers
- Product managers
- Startup founders
- Student project teams
- Business analysts

## 4. User Problem
Users may need to estimate infrastructure expenses before a project is launched. Without a planning tool, it can be difficult to understand the potential total cost and whether a proposed budget is sufficient.

## 5. Functional Requirements
- Users can edit sample service costs.
- Users can enter a monthly budget.
- Users can specify project duration.
- The system calculates monthly and total estimated expenses.
- The system calculates remaining budget and budget utilization.
- Users can review architecture options and project risks.
- Users can print the executive summary.

## 6. Non-Functional Requirements
- The interface should be simple to navigate.
- The website should work in a modern browser.
- Cost calculations should update when inputs change.
- The project should not require cloud credentials to use.
- The application should clearly identify sample estimates.

## 7. Success Criteria
- Cost totals are calculated correctly.
- Budget utilization reflects the entered values.
- The website displays a clear result when costs exceed the budget.
- The print option opens the browser's print workflow.
- The main interface is usable on a desktop or mobile browser.

## 8. Scope Limitations
The initial version is a prototype. It does not fetch real-time cloud prices, authenticate users, save projects to a database, or retrieve actual cloud usage.
