---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1037"
target_object: "T1071.005"
stix_relationship_id: "relationship--9f0abcfc-68b7-4e6c-9b9c-e511fdd2db00"
---
# Relationship 1279: M1037 — mitigates → T1071.005

**Source object:** [[01 ATT&CK/M1037 - Filter Network Traffic|M1037: Filter Network Traffic]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1071.005 - Publish-Subscribe Protocols|T1071.005: Publish/Subscribe Protocols]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Consider filtering publish/subscribe protocol requests to untrusted or known bad resources over irregular ports (e.g. MQTT’s standard ports are 1883 or 8883).

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9f0abcfc-68b7-4e6c-9b9c-e511fdd2db00`.
