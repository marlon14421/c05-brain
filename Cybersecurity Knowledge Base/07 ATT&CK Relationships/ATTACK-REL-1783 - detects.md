---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0451"
target_object: "T1546.013"
stix_relationship_id: "relationship--bfe24cb5-f0d2-44e8-b576-b0550df5e75f"
---
# Relationship 1783: DET0451 — detects → T1546.013

**Source object:** [[01 ATT&CK/DET0451 - Detection Strategy for PowerShell Profile Persistence via profile.ps1 Modification|DET0451: Detection Strategy for PowerShell Profile Persistence via profile.ps1 Modification]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1546.013 - PowerShell Profile|T1546.013: PowerShell Profile]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfe24cb5-f0d2-44e8-b576-b0550df5e75f`.
