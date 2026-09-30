---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0189"
target_object: "T1027.005"
stix_relationship_id: "relationship--1afa36ca-4af6-4032-93be-aae1dd20d923"
---
# Relationship 1572: DET0189 — detects → T1027.005

**Source object:** [[01 ATT&CK/DET0189 - Detection Strategy for Indicator Removal from Tools - Post-AV Evasion Modification|DET0189: Detection Strategy for Indicator Removal from Tools - Post-AV Evasion Modification]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.005 - Indicator Removal from Tools|T1027.005: Indicator Removal from Tools]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1afa36ca-4af6-4032-93be-aae1dd20d923`.
