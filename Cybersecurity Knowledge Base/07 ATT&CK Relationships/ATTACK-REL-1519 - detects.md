---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0306"
target_object: "T1686.002"
stix_relationship_id: "relationship--81ca2e61-d39f-4a2d-810c-e9d5e953ca86"
---
# Relationship 1519: DET0306 — detects → T1686.002

**Source object:** [[01 ATT&CK/DET0306 - Detection of Unauthorized Network Firewall Rule Modification|DET0306: Detection of Unauthorized Network Firewall Rule Modification]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1686.002 - Network Device Firewall|T1686.002: Network Device Firewall]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81ca2e61-d39f-4a2d-810c-e9d5e953ca86`.
