---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-402"
source: MITRE CAPEC
---
# CAPEC-402: Bypassing ATA Password Security — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-402 - Bypassing ATA Password Security|CAPEC-402 source record]]
- Abstraction: Detailed
- Catalog severity: Not stated
- Catalog likelihood: Not stated

## Pattern summary

An adversary exploits a weakness in ATA security on a drive to gain access to the information the drive contains without supplying the proper credentials. ATA Security is often employed to protect hard disk information from unauthorized access. The mechanism requires the user to type in a password before the BIOS is allowed access to drive contents. Some implementations of ATA security will accept the ATA command to update the password without the user having authenticated with the BIOS. This occurs because the security mechanism assumes the user has first authenticated via the BIOS prior to sending commands to the drive. Various methods exist for exploiting this flaw, the most common being installing the ATA protected drive into a system lacking ATA security features (a.k.a. hot swapping). Once the drive is installed into the new system the BIOS can be used to reset the drive password.

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
