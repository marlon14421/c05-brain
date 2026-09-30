---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0149"
target_object: "T1048.003"
stix_relationship_id: "relationship--58e2dcbe-42f7-4c73-b717-696ff56494cb"
---
# Relationship 2074: DET0149 — detects → T1048.003

**Source object:** [[01 ATT&CK/DET0149 - Detection of Exfiltration Over Unencrypted Non-C2 Protocol|DET0149: Detection of Exfiltration Over Unencrypted Non-C2 Protocol]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1048.003 - Exfiltration Over Unencrypted Non-C2 Protocol|T1048.003: Exfiltration Over Unencrypted Non-C2 Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--58e2dcbe-42f7-4c73-b717-696ff56494cb`.
