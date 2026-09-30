---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0503"
target_object: "T1048.001"
stix_relationship_id: "relationship--56d9655a-f594-427f-b487-09f3e3d8fca3"
---
# Relationship 1451: DET0503 — detects → T1048.001

**Source object:** [[01 ATT&CK/DET0503 - Behavioral Detection Strategy for Exfiltration Over Symmetric Encrypted Non-C2 Protoc|DET0503: Behavioral Detection Strategy for Exfiltration Over Symmetric Encrypted Non-C2 Protocol]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1048.001 - Exfiltration Over Symmetric Encrypted Non-C2 Protocol|T1048.001: Exfiltration Over Symmetric Encrypted Non-C2 Protocol]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56d9655a-f594-427f-b487-09f3e3d8fca3`.
