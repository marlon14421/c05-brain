---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1552.004"
stix_relationship_id: "relationship--1d2ee595-1972-46ac-bd85-322bdc5e35de"
---
# Relationship 4165: C0014 — uses → T1552.004

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1552.004 - Private Keys|T1552.004: Private Keys]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), threat actors used [Mimikatz](https://attack.mitre.org/software/S0002) to dump certificates and private keys from the Windows certificate store.(Citation: FoxIT Wocao December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1d2ee595-1972-46ac-bd85-322bdc5e35de`.
