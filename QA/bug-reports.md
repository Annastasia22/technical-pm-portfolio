# Bug Reports

## BUG-001 — Password Reset Token Expires Immediately

### Severity
High

### Environment
Staging

### Description
Users are unable to reset passwords because reset tokens expire immediately after generation.

### Steps to Reproduce
1. Navigate to the login page
2. Click "Forgot Password"
3. Enter a valid email
4. Open password reset email
5. Click the reset link

### Expected Result
The user should successfully access the password reset form.

### Actual Result
System displays:
"Token Expired"

### Impact
Users cannot recover accounts.

### Status
Open

---

## BUG-002 — Duplicate Signup Allowed

### Severity
Medium

### Environment
Staging

### Description
The system allows multiple registrations using the same email address.

### Steps to Reproduce
1. Register a new account
2. Logout
3. Attempt second registration using the same email

### Expected Result
Registration should be blocked.

### Actual Result
Duplicate account created successfully.

### Impact
Potential authentication and account conflicts.

### Status
In Progress
