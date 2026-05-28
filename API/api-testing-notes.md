# API Testing Notes

## Objective

Validate core SaaS platform APIs to ensure stable communication between frontend systems, backend services, and third-party integrations.

---

# Tools Used
- Postman
- Staging Environment
- API Documentation

---

# Authentication API Testing

## Endpoint
POST /api/auth/login

### Validation Areas
- valid credentials
- invalid credentials
- expired sessions
- response status codes
- token generation

### Expected Responses
- 200 Success
- 401 Unauthorised
- 500 Server Error

---

# User Registration API

## Endpoint
POST /api/auth/register

### Validation Areas
- duplicate email prevention
- password validation
- required field validation

---

# Password Reset API

## Endpoint
POST /api/auth/reset-password

### Validation Areas
- token expiration
- invalid token handling
- successful password update

---

# API Regression Areas
- authentication workflows
- user session persistence
- webhook integrations
- notification delivery

---

# Risks Identified
- session timeout instability
- delayed API responses
- third-party integration failures

---

# TPM Responsibilities
- coordinate API validation
- communicate API issues to engineering
- track technical blockers
- validate release readiness
