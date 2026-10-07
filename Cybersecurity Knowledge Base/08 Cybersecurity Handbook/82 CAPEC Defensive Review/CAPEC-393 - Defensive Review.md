---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-393"
source: MITRE CAPEC
---
# CAPEC-393: Lock Picking — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-393 - Lock Picking|CAPEC-393 source record]]
- Abstraction: Detailed
- Catalog severity: Not stated
- Catalog likelihood: Not stated

## Pattern summary

An attacker uses lock picking tools and techniques to bypass the locks on a building or facility. Lock picking is the use of a special set of tools to manipulate the pins within a lock. Different sets of tools are required for each type of lock. Lock picking attacks have the advantage of being non-invasive in that if performed correctly the lock will not be damaged. A standard lock pin-and-tumbler lock is secured by a set of internal pins that prevent the tumbler device from turning. Spring loaded driver pins push down on the key pins preventing rotation so that the bolt remains in a locked position.. When the correct key is inserted, the ridges on the key push the key pins up and against the driver pins, causing correct alignment which allows the lock cylinder to rotate. Most common locks, such as domestic locks in the US, can be picked using a standard 2 tools (i.e. a torsion wrench and a hook pick).

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
