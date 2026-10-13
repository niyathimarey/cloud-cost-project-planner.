
# Cloud Cost & Project Resource Planner

## Overview

A browser-based dashboard that helps project managers estimate cloud infrastructure costs, compare architecture options, assess budget risks, and prepare project summaries.

## Problem Statement

Project teams need to understand expected cloud expenses before launching an application. Poor estimates can cause budget overruns and unnecessary spending.

This project provides a simple planning tool to help teams compare estimates and make more informed decisions.

## Objectives

- Estimate monthly and total project costs.
- Calculate budget utilization and remaining budget.
- Compare two cloud architecture options.
- Assess project risks using likelihood and impact.
- Generate a printable executive summary.

## Features

- Editable AWS service cost estimates
- Budget tracking
- Over-budget warnings
- Serverless versus server-based cost comparison
- Project risk assessment
- Risk mitigation planning
- Printable executive report

## Technologies

- HTML
- CSS
- JavaScript
- GitHub
- GitHub Pages
- AWS Pricing Calculator for external cost estimates

## Live Demo

https://github.com/niyathimarey/cloud-cost-project-planner.

## How to Use

1. Open the live website.
2. Enter the project name, budget, and duration.
3. Update the estimated monthly costs.
4. Review the budget dashboard.
5. Compare two architecture options.
6. Assess project risks.
7. Generate and print the executive summary.

## Project Limitations

This version calculates costs in the browser using manually entered estimates. It does not retrieve live AWS prices, connect to AWS billing APIs, or save user data to a database.

## Future Improvements

- Add cost comparison charts.
- Import estimates from pricing reports.
- Save multiple project scenarios.
- Add an AWS-backed API and database.
- Introduce secure user authentication.
- Explore automated cloud cost reporting.

## Disclaimer

Initial figures are illustrative examples, not official AWS quotations. Actual costs depend on region, usage, configuration, data transfer, taxes, and current pricing.
