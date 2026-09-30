---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0284"
target_object: "T1567.003"
stix_relationship_id: "relationship--7478c9f5-d7a9-4423-9c1f-228bac8eb739"
---
# Relationship 1945: DET0284 — detects → T1567.003

**Source object:** [[01 ATT&CK/DET0284 - Detection Strategy for Exfiltration to Text Storage Sites|DET0284: Detection Strategy for Exfiltration to Text Storage Sites]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1567.003 - Exfiltration to Text Storage Sites|T1567.003: Exfiltration to Text Storage Sites]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7478c9f5-d7a9-4423-9c1f-228bac8eb739`.
