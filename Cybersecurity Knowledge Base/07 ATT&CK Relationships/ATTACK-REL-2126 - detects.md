---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0445"
target_object: "T1090"
stix_relationship_id: "relationship--20b8b8ac-5c86-4dc3-a0e7-394f0e1ed7a9"
---
# Relationship 2126: DET0445 — detects → T1090

**Source object:** [[01 ATT&CK/DET0445 - Detection of Proxy Infrastructure Setup and Traffic Bridging|DET0445: Detection of Proxy Infrastructure Setup and Traffic Bridging]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20b8b8ac-5c86-4dc3-a0e7-394f0e1ed7a9`.
