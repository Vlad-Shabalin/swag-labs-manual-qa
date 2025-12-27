# Test Plan  
**Project:** Swag Labs Web Application

---

## 1. Introduction

This Test Plan describes the testing strategy, scope, approach, and resources
used for manual testing of the Swag Labs web application.
The purpose of testing is to ensure correct functionality of key user flows.

---

## 2. Objectives

The objectives of this testing are:
- Verify core functionality of the application
- Identify functional defects
- Validate user authentication and checkout flows
- Ensure correct behavior for positive and negative scenarios

---

## 3. Application Under Test (AUT)

- Application: Swag Labs
- Type: Web application
- URL: https://www.saucedemo.com/
- Environment: Test environment

### Tested Modules:
- Login
- Logout
- Products
- Cart
- Checkout

---

## 4. Scope of Testing

### In Scope:
- Functional testing
- UI validation
- Input field validation
- Positive and negative test scenarios
- Basic usability testing

### Out of Scope:
- Performance testing
- Security testing
- Automation testing
- Mobile testing
- API testing

---

## 5. Test Approach

Testing is performed manually based on:
- Application behavior
- Test cases
- Checklists

The following test design techniques are used:
- Equivalence Partitioning
- Boundary Value Analysis
- Positive and Negative testing

Defects are reported using Jira-style bug reports.

---

## 6. Test Artifacts

The following test artifacts were created:
- Checklist
- Test Cases
- Bug Reports
- Test Plan
- Test Summary Report

---

## 7. Test Environment

- Browser: Google Chrome
- OS: Windows / macOS
- Device: Desktop
- Internet connection: Stable

---

## 8. Entry Criteria

Testing starts when:
- Application is accessible
- Test environment is ready
- Test cases and checklist are prepared

---

## 9. Exit Criteria

Testing is completed when:
- All planned test cases are executed
- All critical and high severity defects are reported
- Test results are documented

---

## 10. Defect Management

Defects include the following attributes:
- Bug ID
- Title
- Environment
- Preconditions
- Steps to Reproduce
- Actual Result
- Expected Result
- Severity
- Priority
- Status
- Attachments

Severity Levels:
- Critical
- Major
- Minor
- Trivial

Priority Levels:
- High
- Medium
- Low

---

## 11. Risks and Mitigation

| Risk | Mitigation |
|-----|-----------|
| Unclear requirements | Test based on standard expected behavior |
| Limited test environment | Focus on critical functionality |
| Time constraints | Prioritize high-risk scenarios |

---

## 12. Roles and Responsibilities

- Manual QA Engineer:
  - Create test documentation
  - Execute test cases
  - Report defects
  - Prepare test reports

---

## 13. Deliverables

- Completed checklist
- Executed test cases
- Documented bug reports
- Test Plan
- Test Summary Report