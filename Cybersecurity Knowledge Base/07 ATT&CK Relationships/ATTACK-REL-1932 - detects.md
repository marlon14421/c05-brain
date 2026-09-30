---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0876"
target_object: "T1586"
stix_relationship_id: "relationship--addbc146-e378-4ca0-aca1-8de5443af453"
---
# Relationship 1932: DET0876 — detects → T1586

**Source object:** [[01 ATT&CK/DET0876 - Detection of Compromise Accounts|DET0876: Detection of Compromise Accounts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1586 - Compromise Accounts|T1586: Compromise Accounts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--addbc146-e378-4ca0-aca1-8de5443af453`.
