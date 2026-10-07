---
tags:
  - cybersecurity
  - authorized-assessment
  - web-security
section: "Web Authentication Testing"
---
# Step-Up Authentication Triggers

## Focus

Verify reauthentication requirements for high-impact actions and sensitive account changes.

## Assessment method

Establish the expected behavior from requirements and application design. Use dedicated test roles, synthetic records, and a staging or otherwise explicitly approved target. Change one variable at a time, use low-impact requests, and monitor service health. Never use another user's real account or retrieve real sensitive data to prove a finding.

## Review checklist

- Confirm authorization, target, environment, account role, and test window.
- Identify the server-side control and relevant trust boundary.
- Compare expected and observed behavior using minimal, reproducible evidence.
- Consider alternate routes, benign explanations, privacy, and operational impact.
- Stop if the test reaches out-of-scope systems or exposes real sensitive information.

## Defensive outcome

Describe the affected feature, required preconditions, security impact, evidence, confidence, mitigation, and retest criteria. Prefer a root-cause fix and verify it with both a negative case and a legitimate workflow. Keep requests, cookies, and identifiers redacted in reports.

## Safe exercise

Apply **step-up authentication triggers** to a local intentionally vulnerable training app or an owned staging service with written approval. Use only synthetic data. Record the role and expected decision, capture the minimum request/response details needed, then verify remediation and reset test data.

## Further reading

- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [OWASP Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]

## Learning exercise

Write a short test case for **step-up authentication triggers** with a precondition, expected secure result, harmless test input, evidence to retain, and a measurable retest. State the authorization boundary and a stop condition.
