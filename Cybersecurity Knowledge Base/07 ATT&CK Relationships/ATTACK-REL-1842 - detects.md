---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0342"
target_object: "T1218.001"
stix_relationship_id: "relationship--f6a621a4-6a66-492d-82ed-848cc0bcaa76"
---
# Relationship 1842: DET0342 — detects → T1218.001

**Source object:** [[01 ATT&CK/DET0342 - Detection of Suspicious Compiled HTML File Execution via hh.exe|DET0342: Detection of Suspicious Compiled HTML File Execution via hh.exe]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.001 - Compiled HTML File|T1218.001: Compiled HTML File]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f6a621a4-6a66-492d-82ed-848cc0bcaa76`.
