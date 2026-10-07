---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-133"
source: MITRE CAPEC
---
# CAPEC-133: Try All Common Switches — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-133 - Try All Common Switches|CAPEC-133 source record]]
- Abstraction: Standard
- Catalog severity: Medium
- Catalog likelihood: Not stated

## Pattern summary

An attacker attempts to invoke all common switches and options in the target application for the purpose of discovering weaknesses in the target. For example, in some applications, adding a --debug switch causes debugging information to be displayed, which can sometimes reveal sensitive processing or configuration information to an attacker. This attack differs from other forms of API abuse in that the attacker is indiscriminately attempting to invoke options in the hope that one of them will work rather than specifically targeting a known option. Nonetheless, even if the attacker is familiar with the published options of a targeted application this attack method may still be fruitful as it might discover unpublicized functionality.

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
