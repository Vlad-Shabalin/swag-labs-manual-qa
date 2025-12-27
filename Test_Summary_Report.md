# Test Summary Report  
**Project:** Swag Labs Web Application

---

## 1. Introduction

This Test Summary Report provides an overview of the results of manual testing
performed on the Swag Labs web application according to the Test Plan.

---

## 2. Test Scope

### Tested Modules:
- Login
- Logout
- Products
- Cart
- Checkout

### Types of Testing:
- Functional testing
- UI validation
- Input validation
- Positive and negative testing

---

## 3. Test Environment

- Browser: Google Chrome
- OS: Windows / macOS
- Device: Desktop
- Environment: Test environment

---

## 4. Test Execution Summary

| Metric | Count |
|------|------|
| Total Test Cases | 23 |
| Executed Test Cases | 23 |
| Passed | 19 |
| Failed | 4 |
| Blocked | 0 |
| Not Executed | 0 |

---

## 5. Defect Summary

| Severity | Count |
|--------|------|
| Blocker | 1 |
| Critical | 4 |
| Major | 1 |
| Minor | 1 |
| Trivial | 0 |
| **Total** | **7** |

---

## 6. Major Issues Identified

- User is able to log in using invalid credentials
- Error message is not displayed for empty login fields
- Checkout can be completed with missing required information
- UI inconsistency on the Cart page

---

## 7. Overall Quality Assessment

Based on the test execution results:
- Core functionality is partially stable
- One critical defect affects authentication
- Application requires bug fixes before release

---

## 8. Exit Criteria Status

| Exit Criteria | Status |
|--------------|--------|
| All test cases executed | ✅ |
| Critical bugs reported | ✅ |
| Test results documented | ✅ |

Exit criteria are **partially met** due to open critical defects.

---

## 9. Risks and Limitations

- Testing was limited to desktop browsers
- No mobile testing performed
- No backend or API access

---

## 10. Recommendations

- Fix critical and blocker issues
- Perform regression testing after bug fixes
- Extend testing to other browsers and devices

---

## 11. Conclusion

Manual testing of the Swag Labs application was successfully completed.
Several defects were identified and documented.
The application is **not ready for release** until critical issues are resolved.