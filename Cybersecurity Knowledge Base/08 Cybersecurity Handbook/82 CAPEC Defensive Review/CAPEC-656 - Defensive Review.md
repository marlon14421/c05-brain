---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-656"
source: MITRE CAPEC
---
# CAPEC-656: Voice Phishing — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-656 - Voice Phishing|CAPEC-656 source record]]
- Abstraction: Detailed
- Catalog severity: High
- Catalog likelihood: High

## Pattern summary

An adversary targets users with a phishing attack for the purpose of soliciting account passwords or sensitive information from the user. Voice Phishing is a variation of the Phishing social engineering technique where the attack is initiated via a voice call, rather than email. The user is enticed to provide sensitive information by the adversary, who masquerades as a legitimate employee of the alleged organization. Voice Phishing attacks deviate from standard Phishing attacks, in that a user doesn't typically interact with a compromised website to provide sensitive information and instead provides this information verbally. Voice Phishing attacks can also be initiated by either the adversary in the form of a "cold call" or by the victim if calling an illegitimate telephone number.

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
