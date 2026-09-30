---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0586"
target_object: "T1003.003"
stix_relationship_id: "relationship--1f368a24-aeeb-4892-991b-0653a7e13586"
---
# Relationship 1628: DET0586 — detects → T1003.003

**Source object:** [[01 ATT&CK/DET0586 - Detection of NTDS.dit Credential Dumping from Domain Controllers|DET0586: Detection of NTDS.dit Credential Dumping from Domain Controllers]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1f368a24-aeeb-4892-991b-0653a7e13586`.
