---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0077"
target_object: "T1011"
stix_relationship_id: "relationship--9cd323fc-5b81-49ac-9457-4c17292ba25e"
---
# Relationship 1920: DET0077 — detects → T1011

**Source object:** [[01 ATT&CK/DET0077 - Detection of Exfiltration Over Alternate Network Interfaces|DET0077: Detection of Exfiltration Over Alternate Network Interfaces]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1011 - Exfiltration Over Other Network Medium|T1011: Exfiltration Over Other Network Medium]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9cd323fc-5b81-49ac-9457-4c17292ba25e`.
