---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1037"
target_object: "T1190"
stix_relationship_id: "relationship--1c0c0c90-7974-48f4-9de0-15a8d9b00e0a"
---
# Relationship 1019: M1037 — mitigates → T1190

**Source object:** [[01 ATT&CK/M1037 - Filter Network Traffic|M1037: Filter Network Traffic]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Restrict outbound network traffic from public-facing servers to prevent unauthorized connections from initiating communications with attacker-controlled infrastructure. While this may not prevent the initial exploitation, it limits the attacker's ability to verify and control the compromised server post-exploit, reducing the overall impact of the attack.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1c0c0c90-7974-48f4-9de0-15a8d9b00e0a`.
