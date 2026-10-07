# SweetShop Testing – QA & Test Automation Portfolio

A structured software testing portfolio for the SweetShop e-commerce application. This repository demonstrates requirements analysis, test design, functional coverage, defect reporting, test execution reporting, and risk-based scenario planning.

## What this repository demonstrates

- Test planning and scope definition
- Positive, negative, boundary, validation, and usability testing
- End-to-end customer journeys
- Cart, checkout, authentication, search, filtering, and product flows
- Defect documentation with severity and priority
- Regression and smoke test coverage
- Traceability between scenarios and test cases
- Portfolio-ready QA documentation

## Repository contents

| Artifact | Purpose |
|---|---|
| Test_Plan.xlsx | Test objectives, scope, approach, risks, environment, entry/exit criteria |
| Test_Scenarios.xlsx | High-level business and user-flow scenarios |
| Test_Cases.xlsx | Detailed test cases with expected results |
| Bug_Report.xlsx | Defect tracking and triage |
| Test_Summary_Report.xlsx | Execution summary and release assessment |
| Test_Traceability_Matrix.csv | Requirement-to-test coverage matrix |
| Regression_Test_Suite.csv | Prioritized regression/smoke suite |
| QA_Test_Data.csv | Reusable positive and negative test data |
| TESTING_GUIDE.md | How to execute, review, and extend the QA suite |
| .github/workflows/qa-validation.yml | Automated repository QA validation |

## Coverage focus

The expanded suite covers:

1. Application availability and navigation
2. Product catalogue and product details
3. Search and filtering
4. User registration and authentication
5. Cart add/update/remove flows
6. Quantity, price, subtotal, and total calculations
7. Checkout and order placement
8. Invalid input and validation handling
9. Boundary and edge cases
10. Session and state behaviour
11. Responsive/usability checks
12. Security-oriented input validation
13. Regression and release smoke coverage

## Quality goal

The objective is not simply to produce a large number of test cases. The suite emphasizes meaningful risk coverage, clear expected behaviour, reusable test data, traceability, and release confidence.

## Suggested execution model

**Smoke → Functional → Negative/Boundary → Regression → Exploratory → Release decision**

Test results should be recorded with evidence, defect IDs, severity, and retest status.

## Portfolio value

This repository can be presented as a practical QA case study showing how a tester converts product requirements into scenarios, detailed test cases, defects, coverage metrics, and release recommendations.
