# Test Cases — User Authentication

## Objective
Validate core authentication workflows, including login, signup, and password reset functionality.

---

| Test ID | Feature | Test Scenario | Expected Result | Status |
|---|---|---|---|---|
| TC-001 | Login | Valid email and password | User successfully logs in | Pass |
| TC-002 | Login | Invalid password | Error message displayed | Pass |
| TC-003 | Signup | Existing email registration | Registration prevented | Pass |
| TC-004 | Password Reset | Expired reset token | Token expiration message shown | Pass |
| TC-005 | Logout | User clicks logout | Session terminated successfully | Pass |

---

## Regression Areas
- Authentication API
- Session handling
- Email notification workflows
- User access permissions

---

## Notes
Testing is performed in the staging environment before release validation.
