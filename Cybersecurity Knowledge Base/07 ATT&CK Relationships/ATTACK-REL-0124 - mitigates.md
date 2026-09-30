---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1047"
target_object: "T1552.008"
stix_relationship_id: "relationship--7494c5ff-db1c-4bba-8ec0-8a6678b28900"
---
# Relationship 0124: M1047 — mitigates → T1552.008

**Source object:** [[01 ATT&CK/M1047 - Audit|M1047: Audit]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1552.008 - Chat Messages|T1552.008: Chat Messages]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

Preemptively search through communication services to find shared unsecured credentials. Searching for common patterns like " password is ", “ password= ” and take actions to reduce exposure when found.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7494c5ff-db1c-4bba-8ec0-8a6678b28900`.
