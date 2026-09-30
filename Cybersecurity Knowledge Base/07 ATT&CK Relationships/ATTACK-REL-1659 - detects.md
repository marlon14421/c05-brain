---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0136"
target_object: "T1134.005"
stix_relationship_id: "relationship--c38f2585-064d-4dd7-803b-0354512d492a"
---
# Relationship 1659: DET0136 — detects → T1134.005

**Source object:** [[01 ATT&CK/DET0136 - Behavior-chain detection for T1134.005 Access Token Manipulation- SID-History Injecti|DET0136: Behavior-chain detection for T1134.005 Access Token Manipulation: SID-History Injection (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1134.005 - SID-History Injection|T1134.005: SID-History Injection]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c38f2585-064d-4dd7-803b-0354512d492a`.
