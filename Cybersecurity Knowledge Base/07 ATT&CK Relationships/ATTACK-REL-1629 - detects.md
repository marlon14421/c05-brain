---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0162"
target_object: "T1205.002"
stix_relationship_id: "relationship--829a3356-ec45-4101-8eb0-f0c168ff8f03"
---
# Relationship 1629: DET0162 — detects → T1205.002

**Source object:** [[01 ATT&CK/DET0162 - Socket-filter trigger → on-host raw-socket activity → reverse connection (T1205.002)|DET0162: Socket-filter trigger → on-host raw-socket activity → reverse connection (T1205.002)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1205.002 - Socket Filters|T1205.002: Socket Filters]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--829a3356-ec45-4101-8eb0-f0c168ff8f03`.
