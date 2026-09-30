---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0896"
target_object: "T1583.006"
stix_relationship_id: "relationship--a8d3e47e-5158-4183-bab8-b44b43edaf8d"
---
# Relationship 2008: DET0896 — detects → T1583.006

**Source object:** [[01 ATT&CK/DET0896 - Detection of Web Services|DET0896: Detection of Web Services]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1583.006 - Web Services|T1583.006: Web Services]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8d3e47e-5158-4183-bab8-b44b43edaf8d`.
