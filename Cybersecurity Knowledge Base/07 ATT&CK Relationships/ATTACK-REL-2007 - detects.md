---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0006"
target_object: "T1599"
stix_relationship_id: "relationship--b27141c2-b999-468b-bdd3-d2630961dd8b"
---
# Relationship 2007: DET0006 — detects → T1599

**Source object:** [[01 ATT&CK/DET0006 - Detection Strategy for Network Boundary Bridging|DET0006: Detection Strategy for Network Boundary Bridging]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1599 - Network Boundary Bridging|T1599: Network Boundary Bridging]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b27141c2-b999-468b-bdd3-d2630961dd8b`.
