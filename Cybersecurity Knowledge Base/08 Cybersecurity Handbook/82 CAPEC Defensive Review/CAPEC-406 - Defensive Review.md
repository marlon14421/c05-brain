---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-406"
source: MITRE CAPEC
---
# CAPEC-406: Dumpster Diving — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-406 - Dumpster Diving|CAPEC-406 source record]]
- Abstraction: Detailed
- Catalog severity: Low
- Catalog likelihood: Not stated

## Pattern summary

An adversary cases an establishment and searches through trash bins, dumpsters, or areas where company information may have been accidentally discarded for information items which may be useful to the dumpster diver. The devastating nature of the items and/or information found can be anything from medical records, resumes, personal photos and emails, bank statements, account details or information about software, tech support logs and so much more, including hardware devices. By collecting this information an adversary may be able to learn important facts about the person or organization that play a role in helping the adversary in their attack.

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
