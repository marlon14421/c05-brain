---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0332"
target_object: "T1059.010"
stix_relationship_id: "relationship--2fae0b68-3932-4227-a9d0-b3442b0da6f9"
---
# Relationship 1804: DET0332 — detects → T1059.010

**Source object:** [[01 ATT&CK/DET0332 - Detection Strategy for AutoHotKey & AutoIT Abuse|DET0332: Detection Strategy for AutoHotKey & AutoIT Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1059.010 - AutoHotKey & AutoIT|T1059.010: AutoHotKey & AutoIT]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2fae0b68-3932-4227-a9d0-b3442b0da6f9`.
