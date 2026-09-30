---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0848"
target_object: "T1588.004"
stix_relationship_id: "relationship--f0c033e2-a521-4aa6-81a1-2b9f5095d406"
---
# Relationship 1669: DET0848 — detects → T1588.004

**Source object:** [[01 ATT&CK/DET0848 - Detection of Digital Certificates|DET0848: Detection of Digital Certificates]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1588.004 - Digital Certificates|T1588.004: Digital Certificates]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0c033e2-a521-4aa6-81a1-2b9f5095d406`.
