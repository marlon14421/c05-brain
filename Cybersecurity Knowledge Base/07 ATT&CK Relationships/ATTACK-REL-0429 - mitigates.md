---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1051"
target_object: "T1550.002"
stix_relationship_id: "relationship--0c0cd7a2-496b-458d-b041-e05816450502"
---
# Relationship 0429: M1051 — mitigates → T1550.002

**Source object:** [[01 ATT&CK/M1051 - Update Software|M1051: Update Software]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1550.002 - Pass the Hash|T1550.002: Pass the Hash]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Apply patch KB2871997 to Windows 7 and higher systems to limit the default access of accounts in the local administrator group.(Citation: NSA Spotting)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c0cd7a2-496b-458d-b041-e05816450502`.
