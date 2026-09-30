---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0237"
target_object: "T1037.004"
stix_relationship_id: "relationship--00b2d214-7126-4b80-866c-4321d6ace9b0"
---
# Relationship 1535: DET0237 — detects → T1037.004

**Source object:** [[01 ATT&CK/DET0237 - Detection Strategy for Boot or Logon Initialization Scripts- RC Scripts|DET0237: Detection Strategy for Boot or Logon Initialization Scripts: RC Scripts]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1037.004 - RC Scripts|T1037.004: RC Scripts]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00b2d214-7126-4b80-866c-4321d6ace9b0`.
