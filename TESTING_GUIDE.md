# SweetShop QA Testing Guide

## Test levels

### Smoke
Run the critical-path checks first: application access, catalogue loading, product selection, cart, checkout entry, and order submission.

### Functional
Validate each business function independently and then as part of an end-to-end journey.

### Negative and boundary
Use invalid credentials, empty fields, unsupported values, zero/negative quantities, maximum-length inputs, special characters, duplicate actions, and interrupted flows.

### Regression
Re-run the highest-risk tests after every significant change.

## Scenario design technique

For each requirement, consider:
- Happy path
- Alternate path
- Invalid input
- Boundary value
- State transition
- Permission/session behaviour
- Recovery after failure

## Defect quality standard

Every defect should contain:
1. Clear title
2. Preconditions
3. Reproduction steps
4. Expected result
5. Actual result
6. Severity
7. Priority
8. Environment
9. Evidence/reference

## Release recommendation

Recommend release only when critical-path smoke tests pass, no open blocker/critical defects remain, planned functional coverage is complete, and known risks are explicitly accepted.

## Coverage metrics

Track:
- Scenario coverage
- Test-case execution rate
- Pass/fail rate
- Defect density
- Severity distribution
- Requirement traceability
- Regression pass rate
