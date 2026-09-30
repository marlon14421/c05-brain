---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0167"
target_object: "T1495"
stix_relationship_id: "relationship--6279c298-4e08-4cef-89e1-5f90acb2e78e"
---
# Relationship 2115: DET0167 — detects → T1495

**Source object:** [[01 ATT&CK/DET0167 - Firmware Modification via Flash Tool or Corrupted Firmware Upload|DET0167: Firmware Modification via Flash Tool or Corrupted Firmware Upload]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1495 - Firmware Corruption|T1495: Firmware Corruption]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6279c298-4e08-4cef-89e1-5f90acb2e78e`.
