---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1022"
target_object: "T1037.004"
stix_relationship_id: "relationship--116ba54b-b2b3-4e63-9f5b-c5171dde0863"
---
# Relationship 0093: M1022 — mitigates → T1037.004

**Source object:** [[01 ATT&CK/M1022 - Restrict File and Directory Permissions|M1022: Restrict File and Directory Permissions]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1037.004 - RC Scripts|T1037.004: RC Scripts]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Limit privileges of user accounts so only authorized users can edit the `rc.common` file.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--116ba54b-b2b3-4e63-9f5b-c5171dde0863`.
