---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0229"
target_object: "T1087.003"
stix_relationship_id: "relationship--5b441a2e-73b1-4397-9f56-66f642dd26e7"
---
# Relationship 2073: DET0229 — detects → T1087.003

**Source object:** [[01 ATT&CK/DET0229 - Enumeration of Global Address Lists via Email Account Discovery|DET0229: Enumeration of Global Address Lists via Email Account Discovery]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1087.003 - Email Account|T1087.003: Email Account]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b441a2e-73b1-4397-9f56-66f642dd26e7`.
