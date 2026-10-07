---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-31"
source: MITRE CAPEC
---
# CAPEC-31: Accessing/Intercepting/Modifying HTTP Cookies — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-31 - Accessing-Intercepting-Modifying HTTP Cookies|CAPEC-31 source record]]
- Abstraction: Detailed
- Catalog severity: High
- Catalog likelihood: High

## Pattern summary

This attack relies on the use of HTTP Cookies to store credentials, state information and other critical data on client systems. There are several different forms of this attack. The first form of this attack involves accessing HTTP Cookies to mine for potentially sensitive data contained therein. The second form involves intercepting this data as it is transmitted from client to server. This intercepted information is then used by the adversary to impersonate the remote user/session. The third form is when the cookie's content is modified by the adversary before it is sent back to the server. Here the adversary seeks to convince the target server to operate on this falsified information.

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
