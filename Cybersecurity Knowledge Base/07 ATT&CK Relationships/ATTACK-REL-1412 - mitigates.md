---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1017"
target_object: "T1557.004"
stix_relationship_id: "relationship--bb6edf0f-f2c3-4f6d-b545-f79a57423cd2"
---
# Relationship 1412: M1017 — mitigates → T1557.004

**Source object:** [[01 ATT&CK/M1017 - User Training|M1017: User Training]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1557.004 - Evil Twin|T1557.004: Evil Twin]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Train users to be suspicious about access points marked as “Open” or “Unsecure” as well as certificate errors. Certificate errors may arise when the application’s certificate does not match the one expected by the host.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bb6edf0f-f2c3-4f6d-b545-f79a57423cd2`.
