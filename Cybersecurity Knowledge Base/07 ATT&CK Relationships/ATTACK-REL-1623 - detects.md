---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0011"
target_object: "T1001.001"
stix_relationship_id: "relationship--e2b05e19-8a7d-4e1a-8858-545d0fdcb15a"
---
# Relationship 1623: DET0011 — detects → T1001.001

**Source object:** [[01 ATT&CK/DET0011 - Detecting Junk Data in C2 Channels via Behavioral Analysis|DET0011: Detecting Junk Data in C2 Channels via Behavioral Analysis]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1001.001 - Junk Data|T1001.001: Junk Data]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2b05e19-8a7d-4e1a-8858-545d0fdcb15a`.
