---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0818"
target_object: "T1592.003"
stix_relationship_id: "relationship--7ff90051-4d7e-4937-9420-0d8d41eb31b4"
---
# Relationship 1999: DET0818 — detects → T1592.003

**Source object:** [[01 ATT&CK/DET0818 - Detection of Firmware|DET0818: Detection of Firmware]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1592.003 - Firmware|T1592.003: Firmware]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7ff90051-4d7e-4937-9420-0d8d41eb31b4`.
