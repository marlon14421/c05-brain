---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1006"
target_object: "T1018"
stix_relationship_id: "relationship--2bb7ed69-8f59-47f3-8d86-f1c1202c7629"
---
# Relationship 2765: G1006 — uses → T1018

**Source object:** [[01 ATT&CK/G1006 - Earth Lusca|G1006: Earth Lusca]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Earth Lusca](https://attack.mitre.org/groups/G1006) used the command powershell “Get-EventLog -LogName security -Newest 500 | where {$_.EventID -eq 4624} | format-list - property * | findstr “Address”” to find the network information of successfully logged-in accounts to discovery addresses of other machines. [Earth Lusca](https://attack.mitre.org/groups/G1006) has also used multiple scanning tools to discover other machines within the same compromised network.(Citation: TrendMicro EarthLusca 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2bb7ed69-8f59-47f3-8d86-f1c1202c7629`.
