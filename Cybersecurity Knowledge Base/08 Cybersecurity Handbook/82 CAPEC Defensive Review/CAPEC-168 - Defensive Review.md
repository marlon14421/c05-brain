---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-168"
source: MITRE CAPEC
---
# CAPEC-168: Windows ::DATA Alternate Data Stream — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-168 - Windows --DATA Alternate Data Stream|CAPEC-168 source record]]
- Abstraction: Detailed
- Catalog severity: Medium
- Catalog likelihood: Not stated

## Pattern summary

An attacker exploits the functionality of Microsoft NTFS Alternate Data Streams (ADS) to undermine system security. ADS allows multiple "files" to be stored in one directory entry referenced as filename:streamname. One or more alternate data streams may be stored in any file or directory. Normal Microsoft utilities do not show the presence of an ADS stream attached to a file. The additional space for the ADS is not recorded in the displayed file size. The additional space for ADS is accounted for in the used space on the volume. An ADS can be any type of file. ADS are copied by standard Microsoft utilities between NTFS volumes. ADS can be used by an attacker or intruder to hide tools, scripts, and data from detection by normal system utilities. Many anti-virus programs do not check for or scan ADS. Windows Vista does have a switch (-R) on the command line DIR command that will display alternate streams.

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
