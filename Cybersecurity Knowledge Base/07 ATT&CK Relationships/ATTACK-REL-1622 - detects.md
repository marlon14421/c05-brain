---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0376"
target_object: "T1046"
stix_relationship_id: "relationship--56e3bbc8-0ff7-4877-836c-f081261d3a35"
---
# Relationship 1622: DET0376 — detects → T1046

**Source object:** [[01 ATT&CK/DET0376 - Behavioral Detection Strategy for Network Service Discovery Across Platforms|DET0376: Behavioral Detection Strategy for Network Service Discovery Across Platforms]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1046 - Network Service Discovery|T1046: Network Service Discovery]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--56e3bbc8-0ff7-4877-836c-f081261d3a35`.
