# PriceOye E-commerce Website – Manual Testing Project

A manual QA portfolio project covering test planning, scenario design and detailed test case documentation for [PriceOye](https://priceoye.pk/), a Pakistani e-commerce website for mobile phones and electronics.

> **Note:** This is an independent project on a publicly accessible website. No real payments or purchases were made, and no sensitive personal data was used.

## Project Overview

| Item | Details |
| --- | --- |
| System Under Test | PriceOye (https://priceoye.pk/) |
| Application Type | E-commerce web application |
| Testing Approach | Manual testing |
| Environment | Google Chrome, Windows 11, laptop |
| Author | Isha Tahir |
| Test Plan Version | 1.0 (Draft) |

## Scope

**In scope:** Homepage and navigation, product search, categories, filters, sorting, product details, shopping cart, checkout process, input validation.

**Out of scope:** Actual payment transactions, real purchases, server-side code and database testing, security penetration testing, load and stress testing.

## Testing Types Applied

Functional, UI, Positive, Negative, Regression, Exploratory, Usability and Boundary Value Analysis.

## Deliverables

| File | Description |
| --- | --- |
| `PriceOye_Test_Plan_V1.odt` | Test plan: objective, scope, strategy, entry/exit/suspension criteria, environment, schedule, risks |
| `PriceOye_Test_Scenarios_V1.ods` | 41 high-level test scenarios across 8 modules |
| `PriceOye_Test_Cases_V1.ods` | 84 detailed test cases with steps, test data, expected and actual results, priority and status |

## Coverage Summary

**Test scenarios: 41 | Test cases: 84**

| Module | Scenarios | Test Cases |
| --- | --- | --- |
| Homepage | 5 | 11 |
| Product Search | 6 | 14 |
| Product Categories | 5 | 10 |
| Product Filters | 6 | 12 |
| Product Sorting | 4 | 8 |
| Product Details | 5 | 9 |
| Shopping Cart | 6 | 11 |
| Checkout | 4 | 9 |

**Priority split:** 24 High, 47 Medium, 13 Low

**Execution result:** All 84 test cases executed and marked **Pass**.

## Test Case Structure

Each test case includes: Test Case ID, Scenario ID, Module, Test Scenario, Test Type, Priority, Preconditions, Test Data, Test Steps, Expected Result, Actual Result and Status.

Example IDs follow the pattern `TC_<MODULE>_<NUMBER>` (e.g. `TC_HOME_001`) and trace back to scenarios (`TS-001`).

## Defect Management Approach

Any reproducible defect is documented with Bug ID, title, module, steps to reproduce, expected and actual result, severity, priority, status and screenshot/evidence.

## Tools Used

- Google Chrome (and DevTools Network tab for basic load-time checks)
- Spreadsheet software for scenario and test case documentation
- Word processor for the test plan

## Risks Considered

Website downtime, site updates, dynamic product availability, restricted checkout access and network interruptions, each with a planned mitigation (see the test plan, section 9).

## Author

**Isha Tahir**
BS Software Engineering, UMT Lahore
