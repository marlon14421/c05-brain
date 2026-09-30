---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0547"
target_object: "T1505"
stix_relationship_id: "relationship--18790331-6ac1-4274-b7ef-129b7c4b1c7c"
---
# Relationship 1500: DET0547 — detects → T1505

**Source object:** [[01 ATT&CK/DET0547 - Detection Strategy for T1505 - Server Software Component|DET0547: Detection Strategy for T1505 - Server Software Component]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1505 - Server Software Component|T1505: Server Software Component]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--18790331-6ac1-4274-b7ef-129b7c4b1c7c`.
