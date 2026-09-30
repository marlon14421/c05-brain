---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0380"
target_object: "T1005"
stix_relationship_id: "relationship--b10e4a51-3d68-427f-b14d-06c1d81a575d"
---
# Relationship 1533: DET0380 — detects → T1005

**Source object:** [[01 ATT&CK/DET0380 - Detection of Local Data Collection Prior to Exfiltration|DET0380: Detection of Local Data Collection Prior to Exfiltration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1005 - Data from Local System|T1005: Data from Local System]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b10e4a51-3d68-427f-b14d-06c1d81a575d`.
