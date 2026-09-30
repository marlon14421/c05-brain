---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0310"
target_object: "T1098.007"
stix_relationship_id: "relationship--03bbd5b8-e26b-4308-add0-d36a48575b95"
---
# Relationship 1950: DET0310 — detects → T1098.007

**Source object:** [[01 ATT&CK/DET0310 - Suspicious Addition to Local or Domain Groups|DET0310: Suspicious Addition to Local or Domain Groups]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1098.007 - Additional Local or Domain Groups|T1098.007: Additional Local or Domain Groups]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03bbd5b8-e26b-4308-add0-d36a48575b95`.
