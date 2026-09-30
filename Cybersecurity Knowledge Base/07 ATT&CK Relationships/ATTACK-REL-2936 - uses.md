---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0094"
target_object: "T1027.012"
stix_relationship_id: "relationship--7e3091a0-63e3-4cf5-b6c3-ed7e1b11273e"
---
# Relationship 2936: G0094 — uses → T1027.012

**Source object:** [[01 ATT&CK/G0094 - Kimsuky|G0094: Kimsuky]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.012 - LNK Icon Smuggling|T1027.012: LNK Icon Smuggling]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Kimsuky](https://attack.mitre.org/groups/G0094) has used the LNK icon location to execute malicious scripts.(Citation: Aryaka Kimsuky July 2025) [Kimsuky](https://attack.mitre.org/groups/G0094) has also padded the LNK target field properties with extra spaces to obscure the script.(Citation: Securonix Kimsuky February 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e3091a0-63e3-4cf5-b6c3-ed7e1b11273e`.
