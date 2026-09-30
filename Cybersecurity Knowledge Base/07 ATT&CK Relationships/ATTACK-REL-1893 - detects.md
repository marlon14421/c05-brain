---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0518"
target_object: "T1498"
stix_relationship_id: "relationship--372cdf67-89a5-4214-a4c4-d2eadc753fa1"
---
# Relationship 1893: DET0518 — detects → T1498

**Source object:** [[01 ATT&CK/DET0518 - Behavioral Detection of T1498 – Network Denial of Service Across Platforms|DET0518: Behavioral Detection of T1498 – Network Denial of Service Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1498 - Network Denial of Service|T1498: Network Denial of Service]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--372cdf67-89a5-4214-a4c4-d2eadc753fa1`.
