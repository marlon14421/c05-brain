---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1024"
target_object: "T1574.011"
stix_relationship_id: "relationship--469231fb-3797-49bf-9f23-078b37a35671"
---
# Relationship 1262: M1024 — mitigates → T1574.011

**Source object:** [[01 ATT&CK/M1024 - Restrict Registry Permissions|M1024: Restrict Registry Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1574.011 - Services Registry Permissions Weakness|T1574.011: Services Registry Permissions Weakness]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Ensure proper permissions are set for Registry hives to prevent users from modifying keys for system components that may lead to privilege escalation.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--469231fb-3797-49bf-9f23-078b37a35671`.
