---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0592"
target_object: "T1602"
stix_relationship_id: "relationship--68a7cda8-b2cd-4cc1-97d2-39be28357fe5"
---
# Relationship 1773: DET0592 — detects → T1602

**Source object:** [[01 ATT&CK/DET0592 - Detection Strategy for Data from Configuration Repository on Network Devices|DET0592: Detection Strategy for Data from Configuration Repository on Network Devices]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1602 - Data from Configuration Repository|T1602: Data from Configuration Repository]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68a7cda8-b2cd-4cc1-97d2-39be28357fe5`.
