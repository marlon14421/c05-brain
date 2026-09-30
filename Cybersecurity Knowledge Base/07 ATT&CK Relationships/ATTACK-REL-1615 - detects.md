---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0134"
target_object: "T1555.004"
stix_relationship_id: "relationship--cf8d5818-49bb-4b33-a2af-77f1fa5ff5cc"
---
# Relationship 1615: DET0134 — detects → T1555.004

**Source object:** [[01 ATT&CK/DET0134 - Detect Suspicious Access to Windows Credential Manager|DET0134: Detect Suspicious Access to Windows Credential Manager]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555.004 - Windows Credential Manager|T1555.004: Windows Credential Manager]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cf8d5818-49bb-4b33-a2af-77f1fa5ff5cc`.
