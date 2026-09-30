---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0895"
target_object: "T1583"
stix_relationship_id: "relationship--c1778ef8-2a1d-43e7-bb1b-ad41aea30167"
---
# Relationship 1769: DET0895 — detects → T1583

**Source object:** [[01 ATT&CK/DET0895 - Detection of Acquire Infrastructure|DET0895: Detection of Acquire Infrastructure]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1583 - Acquire Infrastructure|T1583: Acquire Infrastructure]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1778ef8-2a1d-43e7-bb1b-ad41aea30167`.
