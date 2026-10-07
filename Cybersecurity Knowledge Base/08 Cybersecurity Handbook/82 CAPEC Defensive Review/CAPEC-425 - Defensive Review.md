---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-425"
source: MITRE CAPEC
---
# CAPEC-425: Target Influence via Framing — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-425 - Target Influence via Framing|CAPEC-425 source record]]
- Abstraction: Standard
- Catalog severity: Low
- Catalog likelihood: Low

## Pattern summary

An adversary uses framing techniques to contextualize a conversation so that the target is more likely to be influenced by the adversary's point of view. Framing is information and experiences in life that alter the way we react to decisions we must make. This type of persuasive technique exploits the way people are conditioned to perceive data and its significance, while avoiding negative or avoidance responses from the target. Rather than a specific technique framing is a methodology of conversation that slowly encourages the target to adopt to the adversary's perspective. One technique of framing is to avoid the use of the word "No" and to contextualize responses in a manner that is positive. When performed skillfully the target is much more likely to volunteer information or perform actions favorable to the adversary.

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
