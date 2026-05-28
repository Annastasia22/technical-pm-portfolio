# QA Workflow SOP

## Objective

Standardise the QA testing and bug management workflow before SaaS product releases.

---

# Scope

This SOP applies to:
- feature validation
- regression testing
- bug reporting
- release readiness workflows

---

# QA Workflow Process

## Step 1 — Feature Ready for QA
The engineering team moves the completed feature to:
> Ready for QA

### Requirements
- Development completed
- Code reviewed
- Deployment to staging environment completed

---

## Step 2 — Functional Testing

QA validates:
- feature functionality
- user workflows
- edge cases
- acceptance criteria

### Deliverables
- test execution results
- failed test reports
- screenshots if necessary

---

## Step 3 — Bug Reporting

Any issues identified are documented with:
- severity level
- reproduction steps
- expected vs actual behaviour

### Bug Severity Levels
- Critical
- High
- Medium
- Low

---

## Step 4 — Regression Testing

QA verifies:
- Recent updates did not break existing functionality
- core workflows remain stable

### Areas Tested
- authentication
- onboarding
- billing
- notifications
- API integrations

---

## Step 5 — UAT Validation

Stakeholders validate:
- business requirements
- user experience
- release readiness

---

## Step 6 — Release Approval

Release approved only after:
- critical bugs resolved
- regression completed
- QA signoff received
- TPM approval completed

---

# Roles & Responsibilities

## Engineering
- fix defects
- deploy fixes
- support QA investigations

## QA
- execute testing
- report defects
- validate fixes

## TPM
- coordinate testing workflow
- track release risks
- communicate status updates
- approve release readiness

---

# Tools Used
- Jira
- Postman
- GitHub
- Staging Environment
