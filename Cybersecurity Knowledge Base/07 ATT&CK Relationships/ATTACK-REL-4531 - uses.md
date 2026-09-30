---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0017"
target_object: "T1036.005"
stix_relationship_id: "relationship--8996ab0b-8bc5-4c17-9bd5-a29b6c771f62"
---
# Relationship 4531: C0017 — uses → T1036.005

**Source object:** [[01 ATT&CK/C0017 - C0017|C0017: C0017]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [C0017](https://attack.mitre.org/campaigns/C0017), [APT41](https://attack.mitre.org/groups/G0096) used file names beginning with USERS, SYSUSER, and SYSLOG for [DEADEYE](https://attack.mitre.org/software/S1052), and changed [KEYPLUG](https://attack.mitre.org/software/S1051) file extensions from .vmp to .upx likely to avoid hunting detections.(Citation: Mandiant APT41)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8996ab0b-8bc5-4c17-9bd5-a29b6c771f62`.
