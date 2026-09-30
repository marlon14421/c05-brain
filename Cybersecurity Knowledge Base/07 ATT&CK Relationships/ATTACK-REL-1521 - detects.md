---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0319"
target_object: "T1136.003"
stix_relationship_id: "relationship--e46022f8-1786-4f05-a64e-547c92b38bae"
---
# Relationship 1521: DET0319 — detects → T1136.003

**Source object:** [[01 ATT&CK/DET0319 - Detection Strategy for T1136.003 - Cloud Account Creation across IaaS, IdP, SaaS, Off|DET0319: Detection Strategy for T1136.003 - Cloud Account Creation across IaaS, IdP, SaaS, Office]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1136.003 - Cloud Account|T1136.003: Cloud Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e46022f8-1786-4f05-a64e-547c92b38bae`.
