---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-413"
source: MITRE CAPEC
---
# CAPEC-413: Pretexting via Tech Support — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-413 - Pretexting via Tech Support|CAPEC-413 source record]]
- Abstraction: Detailed
- Catalog severity: Low
- Catalog likelihood: Not stated

## Pattern summary

An adversary engages in pretexting behavior, assuming the role of a tech support worker, to solicit information from target persons, or manipulate the target into performing an action that serves the adversary's interests. An adversary who uses social engineering to impersonate a tech support worker can have devastating effects on a network. This is an effective attack vector, because it can give an adversary physical access to network computers. It only takes a matter of seconds for someone to compromise a computer with physical access. One of the best technological tools at the disposal of a social engineer, posing as a technical support person, is a USB thumb drive. These are small, easy to conceal, and can be loaded with different payloads depending on what task needs to be done. However, this form of attack does not require physical access as it can also be effectively carried out via phone or email.

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
