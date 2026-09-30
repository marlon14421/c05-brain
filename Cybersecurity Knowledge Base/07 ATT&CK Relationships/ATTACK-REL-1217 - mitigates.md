---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1028"
target_object: "T1011.001"
stix_relationship_id: "relationship--c9bce6d2-de66-4114-9cf6-2be555c35194"
---
# Relationship 1217: M1028 — mitigates → T1011.001

**Source object:** [[01 ATT&CK/M1028 - Operating System Configuration|M1028: Operating System Configuration]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1011.001 - Exfiltration Over Bluetooth|T1011.001: Exfiltration Over Bluetooth]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Prevent the creation of new network adapters where possible.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9bce6d2-de66-4114-9cf6-2be555c35194`.
