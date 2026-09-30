---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0595"
target_object: "T1059.002"
stix_relationship_id: "relationship--96af7164-6259-42cd-9007-e882be986dfa"
---
# Relationship 4027: S0595 — uses → T1059.002

**Source object:** [[01 ATT&CK/S0595 - ThiefQuest|S0595: ThiefQuest]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.002 - AppleScript|T1059.002: AppleScript]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ThiefQuest](https://attack.mitre.org/software/S0595) uses [AppleScript](https://attack.mitre.org/techniques/T1059/002)'s osascript -e command to launch [ThiefQuest](https://attack.mitre.org/software/S0595)'s persistence via [Launch Agent](https://attack.mitre.org/techniques/T1543/001) and [Launch Daemon](https://attack.mitre.org/techniques/T1543/004). (Citation: wardle evilquest parti)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--96af7164-6259-42cd-9007-e882be986dfa`.
