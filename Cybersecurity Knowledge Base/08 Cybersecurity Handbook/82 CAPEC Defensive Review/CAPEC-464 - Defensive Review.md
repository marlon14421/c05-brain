---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-464"
source: MITRE CAPEC
---
# CAPEC-464: Evercookie — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-464 - Evercookie|CAPEC-464 source record]]
- Abstraction: Standard
- Catalog severity: Medium
- Catalog likelihood: Not stated

## Pattern summary

An attacker creates a very persistent cookie that stays present even after the user thinks it has been removed. The cookie is stored on the victim's machine in over ten places. When the victim clears the cookie cache via traditional means inside the browser, that operation removes the cookie from certain places but not others. The malicious code then replicates the cookie from all of the places where it was not deleted to all of the possible storage locations once again. So the victim again has the cookie in all of the original storage locations. In other words, failure to delete the cookie in even one location will result in the cookie's resurrection everywhere. The evercookie will also persist across different browsers because certain stores (e.g., Local Shared Objects) are shared between different browsers.

## Defensive interpretation

This catalog entry describes an attack pattern for threat modeling and defensive analysis. Map the conditions to assets, entry points, and controls in your own environment. Prioritize prevention, safe validation, logging, and incident response; this summary is not an execution guide and does not prove an active threat.

A catalog severity or likelihood rating describes the catalog pattern, not the risk of a specific system. Confirm relevance against asset exposure, implementation, controls, and current evidence.

## Threat modeling questions

- Which asset, user, data, or business process could be affected?
- What preconditions, trust boundaries, identities, or external dependencies are relevant?
- Which preventive control should stop the pattern, and where is it enforced?
- What benign activity could resemble the same signal?
- What evidence can validate the control without affecting real users or data?

## Safe validation

Use a local lab, synthetic data, and dedicated test identities. Begin with design and configuration review; if behavior testing is needed, define written authorization, scope, rate limits, time window, stop conditions, and an owner for recovery. Do not test third-party or production systems without explicit authorization. Avoid retrieving real sensitive data or causing service disruption.

## Defensive control and detection plan

Map the pattern to a specific control owner, expected behavior, telemetry source, alert or review condition, and response action. Test detection with benign simulations or historical sanitized data. Document coverage gaps and false-positive cases. Choose mitigation from current platform guidance and verify the legitimate workflow still functions after the change.

## Finding record

If evidence confirms a weakness, record affected component and version, preconditions, observed behavior, impact, confidence, mitigation, owner, and a measurable retest criterion. Distinguish observed facts from hypotheses; the CAPEC entry alone is not evidence of compromise.

## Further reading

- [MITRE CAPEC](https://capec.mitre.org/)
- [[../../04 Defensive Playbooks/Defensive Playbooks|Defensive Playbooks]]
- [[../../06 Sources/Source Register|Source Register and dataset caveats]]
