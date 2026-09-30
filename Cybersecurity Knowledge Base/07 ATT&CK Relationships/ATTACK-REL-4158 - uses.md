---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0007"
target_object: "T1583.001"
stix_relationship_id: "relationship--c274d8fa-8de4-4108-9d6f-9229edf752af"
---
# Relationship 4158: C0007 — uses → T1583.001

**Source object:** [[01 ATT&CK/C0007 - FunnyDream|C0007: FunnyDream]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1583.001 - Domains|T1583.001: Domains]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [FunnyDream](https://attack.mitre.org/campaigns/C0007), the threat actors registered a variety of domains.(Citation: Bitdefender FunnyDream Campaign November 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c274d8fa-8de4-4108-9d6f-9229edf752af`.
