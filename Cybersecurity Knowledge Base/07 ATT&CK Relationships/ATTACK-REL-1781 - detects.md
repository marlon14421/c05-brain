---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0055"
target_object: "T1615"
stix_relationship_id: "relationship--0c2b1d8f-3f5b-4b3a-b146-83e54685d6b9"
---
# Relationship 1781: DET0055 — detects → T1615

**Source object:** [[01 ATT&CK/DET0055 - Detection strategy for Group Policy Discovery on Windows|DET0055: Detection strategy for Group Policy Discovery on Windows]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1615 - Group Policy Discovery|T1615: Group Policy Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0c2b1d8f-3f5b-4b3a-b146-83e54685d6b9`.
