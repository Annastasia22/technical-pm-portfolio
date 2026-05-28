# Risk Register

## Objective

Track and manage project risks that may impact SaaS product delivery, release stability, or operational workflows.

---

| Risk ID | Risk Description | Impact | Probability | Mitigation Strategy | Status |
|---|---|---|---|---|---|
| RISK-001 | Authentication API instability | High | Medium | Conduct API regression testing before release | Open |
| RISK-002 | Delayed email delivery service | Medium | Medium | Implement retry handling and monitoring | Open |
| RISK-003 | Critical production bug during release | High | Low | Prepare rollback strategy and hotfix process | Open |
| RISK-004 | Sprint scope creep | Medium | High | Enforce sprint scope review process | Monitoring |
| RISK-005 | Third-party webhook failures | Medium | Medium | Add webhook validation and alerting | Open |
| RISK-006 | Incomplete QA coverage | High | Medium | Execute regression checklist prior to deployment | Monitoring |

---

# Risk Severity Definitions

## High
Risk may block release or severely impact users.

## Medium
Risk impacts workflows but does not block core operations.

## Low
Minor operational inconvenience with limited user impact.

---

# TPM Responsibilities
- identify delivery risks
- coordinate mitigation plans
- communicate risks to stakeholders
- monitor operational stability
- track release blockers
