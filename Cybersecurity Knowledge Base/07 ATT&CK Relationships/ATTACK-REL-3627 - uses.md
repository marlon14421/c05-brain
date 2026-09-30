---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1013"
target_object: "T1106"
stix_relationship_id: "relationship--0a3c7f91-6020-46f8-be45-d0a8cf86956e"
---
# Relationship 3627: S1013 — uses → T1106

**Source object:** [[01 ATT&CK/S1013 - ZxxZ|S1013: ZxxZ]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ZxxZ](https://attack.mitre.org/software/S1013) has used API functions such as `Process32First`, `Process32Next`, and `ShellExecuteA`.(Citation: Cisco Talos Bitter Bangladesh May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0a3c7f91-6020-46f8-be45-d0a8cf86956e`.
