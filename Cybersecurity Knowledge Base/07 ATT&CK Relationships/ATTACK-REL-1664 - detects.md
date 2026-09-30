---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0318"
target_object: "T1567.001"
stix_relationship_id: "relationship--c97fce35-747a-489f-9421-808a69e950a4"
---
# Relationship 1664: DET0318 — detects → T1567.001

**Source object:** [[01 ATT&CK/DET0318 - Detection Strategy for Exfiltration to Code Repository|DET0318: Detection Strategy for Exfiltration to Code Repository]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1567.001 - Exfiltration to Code Repository|T1567.001: Exfiltration to Code Repository]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c97fce35-747a-489f-9421-808a69e950a4`.
