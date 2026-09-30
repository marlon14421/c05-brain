---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1543"
stix_relationship_id: "relationship--06ef2810-b641-4142-83af-bbb00a598c11"
---
# Relationship 0400: M1018 — mitigates → T1543

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1543 - Create or Modify System Process|T1543: Create or Modify System Process]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit privileges of user accounts and groups so that only authorized administrators can interact with system-level process changes and service configurations.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--06ef2810-b641-4142-83af-bbb00a598c11`.
