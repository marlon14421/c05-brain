---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0118"
target_object: "T1210"
stix_relationship_id: "relationship--0730d238-c81d-415c-9db5-bff7368114d6"
---
# Relationship 1487: DET0118 — detects → T1210

**Source object:** [[01 ATT&CK/DET0118 - Exploitation of Remote Services – multi-platform lateral movement detection|DET0118: Exploitation of Remote Services – multi-platform lateral movement detection]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0730d238-c81d-415c-9db5-bff7368114d6`.
