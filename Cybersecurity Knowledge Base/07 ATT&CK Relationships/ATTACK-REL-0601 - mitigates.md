---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1011"
stix_relationship_id: "relationship--818e5053-404d-4cc2-ba72-037767737e04"
---
# Relationship 0601: M1028 — mitigates → T1011

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1011 - Exfiltration Over Other Network Medium|T1011: Exfiltration Over Other Network Medium]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent the creation of new network adapters where possible.(Citation: Microsoft GPO Bluetooth FEB 2009)(Citation: TechRepublic Wireless GPO FEB 2009)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--818e5053-404d-4cc2-ba72-037767737e04`.
