---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1552.005"
stix_relationship_id: "relationship--ac4beabf-1644-4386-b34a-ebfc6e3bd3b0"
---
# Relationship 1358: M1042 — mitigates → T1552.005

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1552.005 - Cloud Instance Metadata API|T1552.005: Cloud Instance Metadata API]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disable unnecessary metadata services and restrict or disable insecure versions of metadata services that are in use to prevent adversary access.(Citation: Amazon AWS IMDS V2)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ac4beabf-1644-4386-b34a-ebfc6e3bd3b0`.
