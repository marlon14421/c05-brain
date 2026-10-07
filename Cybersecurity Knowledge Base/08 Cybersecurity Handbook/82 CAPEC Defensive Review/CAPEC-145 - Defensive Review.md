---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-145"
source: MITRE CAPEC
---
# CAPEC-145: Checksum Spoofing — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-145 - Checksum Spoofing|CAPEC-145 source record]]
- Abstraction: Detailed
- Catalog severity: Medium
- Catalog likelihood: Not stated

## Pattern summary

An adversary spoofs a checksum message for the purpose of making a payload appear to have a valid corresponding checksum. Checksums are used to verify message integrity. They consist of some value based on the value of the message they are protecting. Hash codes are a common checksum mechanism. Both the sender and recipient are able to compute the checksum based on the contents of the message. If the message contents change between the sender and recipient, the sender and recipient will compute different checksum values. Since the sender's checksum value is transmitted with the message, the recipient would know that a modification occurred. In checksum spoofing an adversary modifies the message body and then modifies the corresponding checksum so that the recipient's checksum calculation will match the checksum (created by the adversary) in the message. This would prevent the recipient from realizing that a change occurred.

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
