---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0017"
target_object: "T1546.011"
stix_relationship_id: "relationship--d2ad0b63-ab0e-48a3-a8bc-2793f3897358"
---
# Relationship 2099: DET0017 — detects → T1546.011

**Source object:** [[01 ATT&CK/DET0017 - Detection Strategy for Application Shimming via sdbinst.exe and Registry Artifacts (W|DET0017: Detection Strategy for Application Shimming via sdbinst.exe and Registry Artifacts (Windows)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.011 - Application Shimming|T1546.011: Application Shimming]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d2ad0b63-ab0e-48a3-a8bc-2793f3897358`.
