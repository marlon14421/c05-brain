---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0830"
target_object: "T1595"
stix_relationship_id: "relationship--0331868e-bb86-4153-b91e-df857c51bb7e"
---
# Relationship 2128: DET0830 — detects → T1595

**Source object:** [[01 ATT&CK/DET0830 - Detection of Active Scanning|DET0830: Detection of Active Scanning]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1595 - Active Scanning|T1595: Active Scanning]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0331868e-bb86-4153-b91e-df857c51bb7e`.
