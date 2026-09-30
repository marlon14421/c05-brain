---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0328"
target_object: "T1218.003"
stix_relationship_id: "relationship--92a59f27-7dbc-4da9-b17e-816cb90fca1d"
---
# Relationship 1698: DET0328 — detects → T1218.003

**Source object:** [[01 ATT&CK/DET0328 - Detection of Malicious Profile Installation via CMSTP.exe|DET0328: Detection of Malicious Profile Installation via CMSTP.exe]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.003 - CMSTP|T1218.003: CMSTP]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--92a59f27-7dbc-4da9-b17e-816cb90fca1d`.
