---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0467"
target_object: "T1055.005"
stix_relationship_id: "relationship--3a1a518f-f1e0-43c1-8dc2-d514e37b8ed8"
---
# Relationship 1605: DET0467 — detects → T1055.005

**Source object:** [[01 ATT&CK/DET0467 - Detection Strategy for TLS Callback Injection via PE Memory Modification and Hollowin|DET0467: Detection Strategy for TLS Callback Injection via PE Memory Modification and Hollowing]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1055.005 - Thread Local Storage|T1055.005: Thread Local Storage]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3a1a518f-f1e0-43c1-8dc2-d514e37b8ed8`.
