---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0507"
target_object: "T1185"
stix_relationship_id: "relationship--88d75e64-5f13-4017-a635-9a52e3458bb2"
---
# Relationship 1597: DET0507 — detects → T1185

**Source object:** [[01 ATT&CK/DET0507 - Detect browser session hijacking via privilege, handle access, and remote thread into|DET0507: Detect browser session hijacking via privilege, handle access, and remote thread into browsers]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1185 - Browser Session Hijacking|T1185: Browser Session Hijacking]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88d75e64-5f13-4017-a635-9a52e3458bb2`.
