---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1042"
target_object: "T1564.006"
stix_relationship_id: "relationship--1ec28c41-586b-42dc-9400-6e6313e38d84"
---
# Relationship 1252: M1042 — mitigates → T1564.006

**Source object:** [[01 ATT&CK/M1042 - Disable or Remove Feature or Program|M1042: Disable or Remove Feature or Program]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1564.006 - Run Virtual Instance|T1564.006: Run Virtual Instance]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Disable native virtualization technologies such as Hyper-V if not necessary within a given environment. Consider also disabling Windows Sandbox if it is not needed to test or debug applications.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ec28c41-586b-42dc-9400-6e6313e38d84`.
