---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0038"
target_object: "T1078.001"
stix_relationship_id: "relationship--47e6ea9a-cb80-49ba-8a72-bad2eafa7cd8"
---
# Relationship 4931: C0038 — uses → T1078.001

**Source object:** [[01 ATT&CK/C0038 - HomeLand Justice|C0038: HomeLand Justice]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078.001 - Default Accounts|T1078.001: Default Accounts]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [HomeLand Justice](https://attack.mitre.org/campaigns/C0038), threat actors used the built-in administrator account to move laterally using RDP and [Impacket](https://attack.mitre.org/software/S0357).(Citation: Microsoft Albanian Government Attacks September 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--47e6ea9a-cb80-49ba-8a72-bad2eafa7cd8`.
