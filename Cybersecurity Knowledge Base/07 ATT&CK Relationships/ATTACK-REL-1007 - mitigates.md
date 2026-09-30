---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1022"
target_object: "T1222.002"
stix_relationship_id: "relationship--16ef64da-7119-42ad-ad73-e8a34a2b6a0f"
---
# Relationship 1007: M1022 — mitigates → T1222.002

**Source object:** [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022: Restrict File and Directory Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1222.002 - Linux and Mac Permissions|T1222.002: Linux and Mac Permissions]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Applying more restrictive permissions to files and directories could prevent adversaries from modifying the access control lists.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--16ef64da-7119-42ad-ad73-e8a34a2b6a0f`.
