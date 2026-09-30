---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0478"
target_object: "T1204"
stix_relationship_id: "relationship--7a3c280c-1116-4197-812a-e233eb1d5a17"
---
# Relationship 1492: DET0478 — detects → T1204

**Source object:** [[01 ATT&CK/DET0478 - User Execution – multi-surface behavior chain (documents-links → helper-unpacker → LO|DET0478: User Execution – multi-surface behavior chain (documents/links → helper/unpacker → LOLBIN/child → egress)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1204 - User Execution|T1204: User Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a3c280c-1116-4197-812a-e233eb1d5a17`.
