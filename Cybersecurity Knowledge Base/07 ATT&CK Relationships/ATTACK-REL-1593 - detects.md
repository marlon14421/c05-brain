---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0525"
target_object: "T1082"
stix_relationship_id: "relationship--baaaccfe-3c16-4d6b-8b67-279d74ee8da4"
---
# Relationship 1593: DET0525 — detects → T1082

**Source object:** [[01 ATT&CK/DET0525 - System Discovery via Native and Remote Utilities|DET0525: System Discovery via Native and Remote Utilities]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--baaaccfe-3c16-4d6b-8b67-279d74ee8da4`.
