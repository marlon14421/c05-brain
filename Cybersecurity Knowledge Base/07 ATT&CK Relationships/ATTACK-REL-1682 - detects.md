---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0081"
target_object: "T1218"
stix_relationship_id: "relationship--e9264dc5-3daa-4e0b-9021-1df1fdd58b67"
---
# Relationship 1682: DET0081 — detects → T1218

**Source object:** [[01 ATT&CK/DET0081 - Detection of Proxy Execution via Trusted Signed Binaries Across Platforms|DET0081: Detection of Proxy Execution via Trusted Signed Binaries Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218 - System Binary Proxy Execution|T1218: System Binary Proxy Execution]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9264dc5-3daa-4e0b-9021-1df1fdd58b67`.
