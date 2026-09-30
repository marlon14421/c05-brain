---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0594"
target_object: "T1003.006"
stix_relationship_id: "relationship--a279f2fd-fb42-400d-a79a-74084b910dea"
---
# Relationship 2043: DET0594 — detects → T1003.006

**Source object:** [[01 ATT&CK/DET0594 - Detection of Unauthorized DCSync Operations via Replication API Abuse|DET0594: Detection of Unauthorized DCSync Operations via Replication API Abuse]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1003.006 - DCSync|T1003.006: DCSync]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a279f2fd-fb42-400d-a79a-74084b910dea`.
