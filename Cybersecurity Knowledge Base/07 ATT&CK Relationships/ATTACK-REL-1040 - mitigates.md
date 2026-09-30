---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1022"
target_object: "T1548.006"
stix_relationship_id: "relationship--f5b14e1c-a5d6-45fb-b329-793e0a2b7ca4"
---
# Relationship 1040: M1022 — mitigates → T1548.006

**Source object:** [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022: Restrict File and Directory Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1548.006 - TCC Manipulation|T1548.006: TCC Manipulation]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

When using an MDM, ensure the permissions granted are specific to the requirements of the binary. Full Disk Access should be restricted to only necessary binaries in alignment with policy.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f5b14e1c-a5d6-45fb-b329-793e0a2b7ca4`.
