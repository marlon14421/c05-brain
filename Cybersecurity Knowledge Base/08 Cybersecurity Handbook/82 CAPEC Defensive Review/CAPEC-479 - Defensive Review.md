---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-479"
source: MITRE CAPEC
---
# CAPEC-479: Malicious Root Certificate — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-479 - Malicious Root Certificate|CAPEC-479 source record]]
- Abstraction: Detailed
- Catalog severity: Low
- Catalog likelihood: Low

## Pattern summary

An adversary exploits a weakness in authorization and installs a new root certificate on a compromised system. Certificates are commonly used for establishing secure TLS/SSL communications within a web browser. When a user attempts to browse a website that presents a certificate that is not trusted an error message will be displayed to warn the user of the security risk. Depending on the security settings, the browser may not allow the user to establish a connection to the website. Adversaries have used this technique to avoid security warnings prompting users when compromised systems connect over HTTPS to adversary controlled web servers that spoof legitimate websites in order to collect login credentials.

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
