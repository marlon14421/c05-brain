---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0442"
target_object: "T1553.003"
stix_relationship_id: "relationship--1473a2c5-641b-42cb-93ee-9ff61b542453"
---
# Relationship 1478: DET0442 — detects → T1553.003

**Source object:** [[01 ATT&CK/DET0442 - Detection Strategy for Subvert Trust Controls using SIP and Trust Provider Hijacking|DET0442: Detection Strategy for Subvert Trust Controls using SIP and Trust Provider Hijacking.]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1553.003 - SIP and Trust Provider Hijacking|T1553.003: SIP and Trust Provider Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1473a2c5-641b-42cb-93ee-9ff61b542453`.
