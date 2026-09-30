---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "mitigates"
source_object: "M1018"
target_object: "T1685.004"
stix_relationship_id: "relationship--7c080252-2bd3-4fb3-98aa-e822a3703455"
---
# Relationship 1099: M1018 — mitigates → T1685.004

**Source object:** [[01 ATT&CK/M1018 - User Account Management|M1018: User Account Management]]  
**Relationship:** `mitigates`  
**Target object:** [[01 ATT&CK/T1685.004 - Disable or Modify Linux Audit System Log|T1685.004: Disable or Modify Linux Audit System Log]]

## Meaning for defensive analysis

Links a defensive mitigation to the behavior it is intended to reduce. Check implementation details and local constraints before applying it.

## Source description

An adversary must already have root level access on the local system to make full use of this technique; be sure to restrict users and accounts to the least privileges they require.

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7c080252-2bd3-4fb3-98aa-e822a3703455`.
