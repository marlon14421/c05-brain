---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0814"
target_object: "T1589.002"
stix_relationship_id: "relationship--f440acf2-f33b-4153-b761-9b7776e275d5"
---
# Relationship 1912: DET0814 — detects → T1589.002

**Source object:** [[01 ATT&CK/DET0814 - Detection of Email Addresses|DET0814: Detection of Email Addresses]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1589.002 - Email Addresses|T1589.002: Email Addresses]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f440acf2-f33b-4153-b761-9b7776e275d5`.
