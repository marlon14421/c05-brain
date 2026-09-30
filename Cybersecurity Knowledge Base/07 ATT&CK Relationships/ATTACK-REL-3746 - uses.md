---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0051"
target_object: "T1561.001"
stix_relationship_id: "relationship--c2fc39b7-17b5-4ca3-914a-7a5d03146c29"
---
# Relationship 3746: C0051 — uses → T1561.001

**Source object:** [[01 ATT&CK/C0051 - APT28 Nearest Neighbor Campaign|C0051: APT28 Nearest Neighbor Campaign]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [APT28 Nearest Neighbor Campaign](https://attack.mitre.org/campaigns/C0051), [APT28](https://attack.mitre.org/groups/G0007) used the native Microsoft utility [cipher.exe](https://attack.mitre.org/software/S1205) to securely wipe files and folders – overwriting the deleted data using cmd.exe /c cipher /W:C .(Citation: Nearest Neighbor Volexity)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c2fc39b7-17b5-4ca3-914a-7a5d03146c29`.
