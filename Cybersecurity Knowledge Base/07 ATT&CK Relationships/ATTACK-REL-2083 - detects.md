---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0300"
target_object: "T1620"
stix_relationship_id: "relationship--f31bc342-0f87-404e-b0b0-bfd810fac18c"
---
# Relationship 2083: DET0300 — detects → T1620

**Source object:** [[01 ATT&CK/DET0300 - Detection Strategy for Reflective Code Loading|DET0300: Detection Strategy for Reflective Code Loading]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f31bc342-0f87-404e-b0b0-bfd810fac18c`.
