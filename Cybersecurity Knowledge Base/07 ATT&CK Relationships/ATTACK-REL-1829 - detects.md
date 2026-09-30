---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0527"
target_object: "T1036.002"
stix_relationship_id: "relationship--3d514683-576d-46c8-b7ab-8bc67f08fc97"
---
# Relationship 1829: DET0527 — detects → T1036.002

**Source object:** [[01 ATT&CK/DET0527 - Right-to-Left Override Masquerading Detection via Filename and Execution Context|DET0527: Right-to-Left Override Masquerading Detection via Filename and Execution Context]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.002 - Right-to-Left Override|T1036.002: Right-to-Left Override]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d514683-576d-46c8-b7ab-8bc67f08fc97`.
