---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0240"
target_object: "T1649"
stix_relationship_id: "relationship--12a19faf-b1ea-4eee-b921-059a2f65622a"
---
# Relationship 2036: DET0240 — detects → T1649

**Source object:** [[01 ATT&CK/DET0240 - Detection Strategy for Steal or Forge Authentication Certificates|DET0240: Detection Strategy for Steal or Forge Authentication Certificates]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1649 - Steal or Forge Authentication Certificates|T1649: Steal or Forge Authentication Certificates]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12a19faf-b1ea-4eee-b921-059a2f65622a`.
