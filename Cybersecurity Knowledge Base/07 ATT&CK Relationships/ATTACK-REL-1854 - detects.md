---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0448"
target_object: "T1055.014"
stix_relationship_id: "relationship--99274045-04a8-4149-bb9f-6017a78c377c"
---
# Relationship 1854: DET0448 — detects → T1055.014

**Source object:** [[01 ATT&CK/DET0448 - Detection Strategy for VDSO Hijacking on Linux|DET0448: Detection Strategy for VDSO Hijacking on Linux]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.014 - VDSO Hijacking|T1055.014: VDSO Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--99274045-04a8-4149-bb9f-6017a78c377c`.
