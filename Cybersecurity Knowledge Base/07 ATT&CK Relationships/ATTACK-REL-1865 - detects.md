---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "detects"
source_object: "DET0359"
target_object: "T1090.003"
stix_relationship_id: "relationship--393a41c9-3c31-4325-9af0-c7601db3cc77"
---
# Relationship 1865: DET0359 — detects → T1090.003

**Source object:** [[01 ATT&CK/DET0359 - Multi-hop Proxy Behavior via Relay Node Chaining, Onion Routing, and Network Tunnelin|DET0359: Multi-hop Proxy Behavior via Relay Node Chaining, Onion Routing, and Network Tunneling]]  
**Relationship:** `detects`  
**Target object:** [[01 ATT&CK/T1090.003 - Multi-hop Proxy|T1090.003: Multi-hop Proxy]]

## Meaning for defensive analysis

Links a detection strategy or analytic to the behavior it can help identify. Validate required telemetry, coverage, and false positives.

## Source description

The STIX relationship has no separate prose description. Its meaning is represented by the typed edge and linked source objects.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--393a41c9-3c31-4325-9af0-c7601db3cc77`.
