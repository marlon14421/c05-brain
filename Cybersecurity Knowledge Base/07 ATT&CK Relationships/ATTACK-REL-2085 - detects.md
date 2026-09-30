---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0007"
target_object: "T1482"
stix_relationship_id: "relationship--fee2c7b4-9246-4abb-af00-64175d16fc8d"
---
# Relationship 2085: DET0007 — detects → T1482

**Source object:** [[01 ATT&CK/DET0007 - Detection of Domain Trust Discovery via API, Script, and CLI Enumeration|DET0007: Detection of Domain Trust Discovery via API, Script, and CLI Enumeration]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1482 - Domain Trust Discovery|T1482: Domain Trust Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fee2c7b4-9246-4abb-af00-64175d16fc8d`.
