---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-161"
source: MITRE CAPEC
---
# CAPEC-161: Infrastructure Manipulation — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-161 - Infrastructure Manipulation|CAPEC-161 source record]]
- Abstraction: Meta
- Catalog severity: High
- Catalog likelihood: Not stated

## Pattern summary

An attacker exploits characteristics of the infrastructure of a network entity in order to perpetrate attacks or information gathering on network objects or effect a change in the ordinary information flow between network objects. Most often, this involves manipulation of the routing of network messages so, instead of arriving at their proper destination, they are directed towards an entity of the attackers' choosing, usually a server controlled by the attacker. The victim is often unaware that their messages are not being processed correctly. For example, a targeted client may believe they are connecting to their own bank but, in fact, be connecting to a Pharming site controlled by the attacker which then collects the user's login information in order to hijack the actual bank account.

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
