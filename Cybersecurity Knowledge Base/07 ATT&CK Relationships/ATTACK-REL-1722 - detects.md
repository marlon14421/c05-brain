---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0153"
target_object: "T1567.004"
stix_relationship_id: "relationship--820a1ffe-27dd-4c0f-a791-f721d5662f5f"
---
# Relationship 1722: DET0153 — detects → T1567.004

**Source object:** [[01 ATT&CK/DET0153 - Detection Strategy for Exfiltration Over Webhook|DET0153: Detection Strategy for Exfiltration Over Webhook]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1567.004 - Exfiltration Over Webhook|T1567.004: Exfiltration Over Webhook]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--820a1ffe-27dd-4c0f-a791-f721d5662f5f`.
