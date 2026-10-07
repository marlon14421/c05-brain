---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-641"
source: MITRE CAPEC
---
# CAPEC-641: DLL Side-Loading — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-641 - DLL Side-Loading|CAPEC-641 source record]]
- Abstraction: Detailed
- Catalog severity: High
- Catalog likelihood: Low

## Pattern summary

An adversary places a malicious version of a Dynamic-Link Library (DLL) in the Windows Side-by-Side (WinSxS) directory to trick the operating system into loading this malicious DLL instead of a legitimate DLL. Programs specify the location of the DLLs to load via the use of WinSxS manifests or DLL redirection and if they aren't used then Windows searches in a predefined set of directories to locate the file. If the applications improperly specify a required DLL or WinSxS manifests aren't explicit about the characteristics of the DLL to be loaded, they can be vulnerable to side-loading.

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
