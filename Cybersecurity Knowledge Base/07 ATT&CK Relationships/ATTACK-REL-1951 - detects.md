---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0396"
target_object: "T1555.001"
stix_relationship_id: "relationship--2be99b50-1b1d-4188-adcb-9a5ad1da1026"
---
# Relationship 1951: DET0396 — detects → T1555.001

**Source object:** [[01 ATT&CK/DET0396 - Detect Access to macOS Keychain for Credential Theft|DET0396: Detect Access to macOS Keychain for Credential Theft]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1555.001 - Keychain|T1555.001: Keychain]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2be99b50-1b1d-4188-adcb-9a5ad1da1026`.
