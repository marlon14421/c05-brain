---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1205"
target_object: "T1561.001"
stix_relationship_id: "relationship--0d5f23ec-c707-4c22-b467-e1776240a923"
---
# Relationship 4189: S1205 — uses → T1561.001

**Source object:** [[01 ATT&CK/S1205 - cipher.exe|S1205: cipher.exe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.001 - Disk Content Wipe|T1561.001: Disk Content Wipe]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[cipher.exe](https://attack.mitre.org/software/S1205) can be used to overwrite deleted data in specified folders.(Citation: Nearest Neighbor Volexity)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0d5f23ec-c707-4c22-b467-e1776240a923`.
