---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0873"
target_object: "T1585"
stix_relationship_id: "relationship--0c4c2d92-3e46-420b-aec9-addb022a5deb"
---
# Relationship 1632: DET0873 — detects → T1585

**Source object:** [[01 ATT&CK/DET0873 - Detection of Establish Accounts|DET0873: Detection of Establish Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1585 - Establish Accounts|T1585: Establish Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c4c2d92-3e46-420b-aec9-addb022a5deb`.
