---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0832"
target_object: "T1596.002"
stix_relationship_id: "relationship--d1ad37d8-6725-4504-ba1e-b9e3b455f2ab"
---
# Relationship 1589: DET0832 — detects → T1596.002

**Source object:** [[01 ATT&CK/DET0832 - Detection of WHOIS|DET0832: Detection of WHOIS]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1596.002 - WHOIS|T1596.002: WHOIS]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d1ad37d8-6725-4504-ba1e-b9e3b455f2ab`.
