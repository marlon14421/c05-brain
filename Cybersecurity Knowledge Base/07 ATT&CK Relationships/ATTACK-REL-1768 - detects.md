---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0226"
target_object: "T1036.008"
stix_relationship_id: "relationship--fd569220-693b-46da-a457-8ea314dce886"
---
# Relationship 1768: DET0226 — detects → T1036.008

**Source object:** [[01 ATT&CK/DET0226 - Detection Strategy for Masquerading via File Type Modification|DET0226: Detection Strategy for Masquerading via File Type Modification]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1036.008 - Masquerade File Type|T1036.008: Masquerade File Type]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fd569220-693b-46da-a457-8ea314dce886`.
