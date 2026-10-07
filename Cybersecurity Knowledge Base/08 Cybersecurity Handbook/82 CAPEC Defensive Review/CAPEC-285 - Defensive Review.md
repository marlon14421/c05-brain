---
tags:
  - cybersecurity
  - defensive-security
  - attack-pattern-review
capec: "CAPEC-285"
source: MITRE CAPEC
---
# CAPEC-285: ICMP Echo Request Ping — Defensive Review

## Source record

- Catalog entry: [[03 Attack Patterns CAPEC/CAPEC-285 - ICMP Echo Request Ping|CAPEC-285 source record]]
- Abstraction: Detailed
- Catalog severity: Low
- Catalog likelihood: Medium

## Pattern summary

An adversary sends out an ICMP Type 8 Echo Request, commonly known as a 'Ping', in order to determine if a target system is responsive. If the request is not blocked by a firewall or ACL, the target host will respond with an ICMP Type 0 Echo Reply datagram. This type of exchange is usually referred to as a 'Ping' due to the Ping utility present in almost all operating systems. Ping, as commonly implemented, allows a user to test for alive hosts, measure round-trip time, and measure the percentage of packet loss.

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
