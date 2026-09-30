---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0050"
target_object: "T1070.006"
stix_relationship_id: "relationship--71a8ae5e-3a78-49b5-9857-e202d636cedf"
---
# Relationship 4501: G0050 — uses → T1070.006

**Source object:** [[01 ATT&CK/G0050 - APT32|G0050: APT32]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.006 - Timestomp|T1070.006: Timestomp]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[APT32](https://attack.mitre.org/groups/G0050) has used scheduled task raw XML with a backdated timestamp of June 2, 2016. The group has also set the creation time of the files dropped by the second stage of the exploit to match the creation time of kernel32.dll. Additionally, [APT32](https://attack.mitre.org/groups/G0050) has used a random value to modify the timestamp of the file storing the clientID.(Citation: FireEye APT32 May 2017)(Citation: ESET OceanLotus Mar 2019)(Citation: ESET OceanLotus macOS April 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71a8ae5e-3a78-49b5-9857-e202d636cedf`.
