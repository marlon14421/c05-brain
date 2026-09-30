---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1040"
target_object: "T1055.015"
stix_relationship_id: "relationship--ffe0659a-ff5b-4ffb-a842-38bb630fd6b8"
---
# Relationship 0034: M1040 — mitigates → T1055.015

**Source object:** [[01 ATT&CK/M1040 - Behavior Prevention on Endpoint|M1040: Behavior Prevention on Endpoint]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1055.015 - ListPlanting|T1055.015: ListPlanting]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Some endpoint security solutions can be configured to block some types of process injection based on common sequences of behavior that occur during the injection process.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ffe0659a-ff5b-4ffb-a842-38bb630fd6b8`.
