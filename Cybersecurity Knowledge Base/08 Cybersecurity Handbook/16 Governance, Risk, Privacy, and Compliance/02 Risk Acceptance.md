---
tags:
  - cybersecurity
  - defensive-security
  - learning-note
section: "Governance, Risk, Privacy, and Compliance"
---
# Risk Acceptance

## Focus

Require accountable approval, explicit scope, compensating controls, expiry, and a reassessment trigger.

## Why it matters

Risk Acceptance is useful when it supports a concrete security decision: what to protect, what evidence to trust, what action is authorized, and how to confirm the result. Keep assumptions visible and distinguish observed facts from analysis. The right control depends on the system, threat model, operational constraints, and current vendor guidance.

## Practical review

- Identify the asset, owner, scope, and security objective.
- Establish a baseline and the source, timestamp, and limitations of evidence.
- Check access, configuration, dependencies, logging, and recovery implications relevant to this topic.
- Consider legitimate activity and alternative explanations before escalating a signal.
- Record the recommended action, responsible owner, rollback or recovery path, and validation criteria.

## Safe exercise

Involve accountable business, legal, privacy, and security owners as required; protect sensitive records and avoid unsupported compliance claims. Apply the concept to a fictional service or sanitized process, identify an owner, evidence source, and review trigger.

## Record the result

Capture the scenario and scope, environment and versions, method, observations, interpretation, uncertainty, and next action. Use synthetic or minimized data. A useful result is reproducible by another authorized practitioner and has a clear retest condition.

## Further reading

- [NIST Cybersecurity Framework](https://www.nist.gov/cyberframework)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]

## Discussion prompt

For **risk acceptance**, what evidence would change your initial assessment? State one plausible benign explanation and one control or recovery measure that can be verified without affecting an unauthorized system.
