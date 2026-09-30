---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0123"
target_object: "T1052"
stix_relationship_id: "relationship--c5916728-0360-40c3-84f7-0f47a47f828f"
---
# Relationship 1946: DET0123 — detects → T1052

**Source object:** [[01 ATT&CK/DET0123 - Detection of Data Exfiltration via Removable Media|DET0123: Detection of Data Exfiltration via Removable Media]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1052 - Exfiltration Over Physical Medium|T1052: Exfiltration Over Physical Medium]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5916728-0360-40c3-84f7-0f47a47f828f`.
