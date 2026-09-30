---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1202"
target_object: "T1218.003"
stix_relationship_id: "relationship--59aa96b0-ea78-49f4-87d7-367550846ea0"
---
# Relationship 4761: S1202 — uses → T1218.003

**Source object:** [[01 ATT&CK/S1202 - LockBit 3.0|S1202: LockBit 3.0]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.003 - CMSTP|T1218.003: CMSTP]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[LockBit 3.0](https://attack.mitre.org/software/S1202) can attempt a CMSTP UAC bypass if it does not have administrative privileges.(Citation: Sentinel Labs LockBit 3.0 JUL 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--59aa96b0-ea78-49f4-87d7-367550846ea0`.
