---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1048"
target_object: "T1211"
stix_relationship_id: "relationship--eb812961-ecb7-4361-82c4-fb52fa93c80b"
---
# Relationship 0316: M1048 — mitigates → T1211

**Source object:** [[01 ATT&CK/M1048 - Application Isolation and Sandboxing|M1048: Application Isolation and Sandboxing]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1211 - Exploitation for Stealth|T1211: Exploitation for Stealth]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Make it difficult for adversaries to advance their operation through exploitation of undiscovered or unpatched vulnerabilities by using sandboxing. Other types of virtualization and application microsegmentation may also mitigate the impact of some types of exploitation. Risks of additional exploits and weaknesses in these systems may still exist. (Citation: Ars Technica Pwn2Own 2017 VM Escape)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb812961-ecb7-4361-82c4-fb52fa93c80b`.
