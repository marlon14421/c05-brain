---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0194"
target_object: "T1218.002"
stix_relationship_id: "relationship--82a7ec61-7aa6-426e-b469-342388735ee2"
---
# Relationship 2143: DET0194 — detects → T1218.002

**Source object:** [[01 ATT&CK/DET0194 - Detection of Malicious Control Panel Item Execution via control.exe or Rundll32|DET0194: Detection of Malicious Control Panel Item Execution via control.exe or Rundll32]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1218.002 - Control Panel|T1218.002: Control Panel]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--82a7ec61-7aa6-426e-b469-342388735ee2`.
