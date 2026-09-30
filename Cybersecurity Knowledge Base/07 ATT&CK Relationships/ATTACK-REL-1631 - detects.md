---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0526"
target_object: "T1560"
stix_relationship_id: "relationship--162725e0-fc79-42ea-95a3-436b1f772d5b"
---
# Relationship 1631: DET0526 — detects → T1560

**Source object:** [[01 ATT&CK/DET0526 - Detect Archiving and Encryption of Collected Data (T1560)|DET0526: Detect Archiving and Encryption of Collected Data (T1560)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1560 - Archive Collected Data|T1560: Archive Collected Data]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--162725e0-fc79-42ea-95a3-436b1f772d5b`.
