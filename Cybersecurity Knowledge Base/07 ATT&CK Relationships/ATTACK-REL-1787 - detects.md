---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0554"
target_object: "T1011.001"
stix_relationship_id: "relationship--7fa3a461-4e83-4a59-9909-479d2879a1a4"
---
# Relationship 1787: DET0554 — detects → T1011.001

**Source object:** [[01 ATT&CK/DET0554 - Detection of Bluetooth-Based Data Exfiltration|DET0554: Detection of Bluetooth-Based Data Exfiltration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1011.001 - Exfiltration Over Bluetooth|T1011.001: Exfiltration Over Bluetooth]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7fa3a461-4e83-4a59-9909-479d2879a1a4`.
