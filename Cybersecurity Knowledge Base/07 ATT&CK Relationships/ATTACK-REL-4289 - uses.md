---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "T1588.002"
stix_relationship_id: "relationship--c0c1a394-23db-44cf-a922-89e10ba13ec6"
---
# Relationship 4289: C0018 — uses → T1588.002

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.002 - Tool|T1588.002: Tool]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

For [C0018](https://attack.mitre.org/campaigns/C0018), the threat actors acquired a variety of open source tools, including [Mimikatz](https://attack.mitre.org/software/S0002), [Sliver](https://attack.mitre.org/software/S0633), SoftPerfect Network Scanner, AnyDesk, and PDQ Deploy.(Citation: Cisco Talos Avos Jun 2022)(Citation: Costa AvosLocker May 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c0c1a394-23db-44cf-a922-89e10ba13ec6`.
