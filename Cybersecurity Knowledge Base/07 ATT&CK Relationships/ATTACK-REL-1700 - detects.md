---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0273"
target_object: "T1573"
stix_relationship_id: "relationship--2b484619-c72b-457d-b362-ceb882438231"
---
# Relationship 1700: DET0273 — detects → T1573

**Source object:** [[01 ATT&CK/DET0273 - Detection Strategy for Encrypted Channel across OS Platforms|DET0273: Detection Strategy for Encrypted Channel across OS Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1573 - Encrypted Channel|T1573: Encrypted Channel]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b484619-c72b-457d-b362-ceb882438231`.
