---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0087"
target_object: "T1027.013"
stix_relationship_id: "relationship--579a5b5b-38be-48df-8fe7-0718578149fa"
---
# Relationship 1467: DET0087 — detects → T1027.013

**Source object:** [[01 ATT&CK/DET0087 - Encrypted or Encoded File Payload Detection Strategy|DET0087: Encrypted or Encoded File Payload Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--579a5b5b-38be-48df-8fe7-0718578149fa`.
