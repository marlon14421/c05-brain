---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0010"
target_object: "T1027.005"
stix_relationship_id: "relationship--fe9c9381-99d7-4798-ab41-3e5cdbda5e21"
---
# Relationship 3130: G0010 — uses → T1027.005

**Source object:** [[01 ATT&CK/G0010 - Turla|G0010: Turla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.005 - Indicator Removal from Tools|T1027.005: Indicator Removal from Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

Based on comparison of [Gazer](https://attack.mitre.org/software/S0168) versions, [Turla](https://attack.mitre.org/groups/G0010) made an effort to obfuscate strings in the malware that could be used as IoCs, including the mutex name and named pipe.(Citation: ESET Gazer Aug 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fe9c9381-99d7-4798-ab41-3e5cdbda5e21`.
