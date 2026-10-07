---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-394"
source: MITRE CAPEC
---
# CAPEC-394: Using a Snap Gun Lock to Force a Lock — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-394 - Using a Snap Gun Lock to Force a Lock|CAPEC-394 source record]]
- Abstraction: Detailed
- Catalog severity: Not stated
- Catalog likelihood: Not stated

## Pattern summary

An attacker uses a Snap Gun, also known as a Pick Gun, to force the lock on a building or facility. A Pick Gun is a special type of lock picking instrument that works on similar principles as lock bumping. A snap gun is a hand-held device with an attached metal pick. The metal pick strikes the pins within the lock, transferring motion from the key pins to the driver pins and forcing the lock into momentary alignment. A standard lock is secured by a set of internal pins that prevent the device from turning. Spring loaded driver pins push down on the key pins. When the correct key is inserted, the ridges on the key push the key pins up and against the driver pins, causing correct alignment which allows the lock cylinder to rotate. A Snap Gun exploits this design by using a metal pin to strike all of the key pins at once, forcing the driver pins to shift into an unlocked position. Unlike bump keys or lock picks, a Snap Gun may damage the lock more easily, leaving evidence that the lock has been tampered with.

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
