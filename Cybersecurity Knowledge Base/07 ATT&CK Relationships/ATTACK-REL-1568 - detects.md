---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0111"
target_object: "T1552.008"
stix_relationship_id: "relationship--3835701f-3809-45a4-91d4-569fc9e70ef9"
---
# Relationship 1568: DET0111 — detects → T1552.008

**Source object:** [[01 ATT&CK/DET0111 - Detect Unsecured Credentials Shared in Chat Messages|DET0111: Detect Unsecured Credentials Shared in Chat Messages]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1552.008 - Chat Messages|T1552.008: Chat Messages]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3835701f-3809-45a4-91d4-569fc9e70ef9`.
