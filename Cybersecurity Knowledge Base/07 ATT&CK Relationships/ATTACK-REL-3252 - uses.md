---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1006"
target_object: "T1210"
stix_relationship_id: "relationship--495db551-b69c-482e-b242-831011c054f7"
---
# Relationship 3252: G1006 — uses → T1210

**Source object:** [[01 ATT&CK/G1006 - Earth Lusca|G1006: Earth Lusca]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Earth Lusca](https://attack.mitre.org/groups/G1006) has used [Mimikatz](https://attack.mitre.org/software/S0002) to exploit a domain controller via the ZeroLogon exploit (CVE-2020-1472).(Citation: TrendMicro EarthLusca 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--495db551-b69c-482e-b242-831011c054f7`.
