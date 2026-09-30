---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0195"
target_object: "T1016"
stix_relationship_id: "relationship--229b177b-8a94-4206-b6d9-9c295604df22"
---
# Relationship 1817: DET0195 — detects → T1016

**Source object:** [[01 ATT&CK/DET0195 - Behavioral Detection of System Network Configuration Discovery|DET0195: Behavioral Detection of System Network Configuration Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--229b177b-8a94-4206-b6d9-9c295604df22`.
