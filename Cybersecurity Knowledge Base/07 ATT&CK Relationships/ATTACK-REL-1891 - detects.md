---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0537"
target_object: "T1195"
stix_relationship_id: "relationship--5f50e76f-fc9b-4f3f-948f-408f58ab2894"
---
# Relationship 1891: DET0537 — detects → T1195

**Source object:** [[01 ATT&CK/DET0537 - Behavioral detection for Supply Chain Compromise (package-update tamper → install → f|DET0537: Behavioral detection for Supply Chain Compromise (package/update tamper → install → first-run)]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1195 - Supply Chain Compromise|T1195: Supply Chain Compromise]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5f50e76f-fc9b-4f3f-948f-408f58ab2894`.
