---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0872"
target_object: "T1587.001"
stix_relationship_id: "relationship--0ed03b6e-a40c-433c-b1fb-e01bf175745c"
---
# Relationship 1525: DET0872 — detects → T1587.001

**Source object:** [[01 ATT&CK/DET0872 - Detection of Malware|DET0872: Detection of Malware]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1587.001 - Malware|T1587.001: Malware]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0ed03b6e-a40c-433c-b1fb-e01bf175745c`.
