---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0397"
target_object: "T1020"
stix_relationship_id: "relationship--38c1f601-496a-4dcd-8109-176c544ab800"
---
# Relationship 1661: DET0397 — detects → T1020

**Source object:** [[01 ATT&CK/DET0397 - Automated Exfiltration Detection Strategy|DET0397: Automated Exfiltration Detection Strategy]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--38c1f601-496a-4dcd-8109-176c544ab800`.
