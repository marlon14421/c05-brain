---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1029"
target_object: "T1070.003"
stix_relationship_id: "relationship--75116ba9-f247-4c5b-b966-007bb61517e5"
---
# Relationship 1215: M1029 — mitigates → T1070.003

**Source object:** [[01 ATT&CK/M1029 - Remote Data Storage|M1029: Remote Data Storage]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1070.003 - Clear Command History|T1070.003: Clear Command History]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Forward logging of historical data to remote data store and centralized logging solution to preserve historical command line log data.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75116ba9-f247-4c5b-b966-007bb61517e5`.
