---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0014"
target_object: "T1558.003"
stix_relationship_id: "relationship--827cbddc-3e19-4aff-a27a-5cce63812d44"
---
# Relationship 2942: C0014 — uses → T1558.003

**Source object:** [[01 ATT&CK/C0014 - Operation Wocao|C0014: Operation Wocao]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1558.003 - Kerberoasting|T1558.003: Kerberoasting]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

During [Operation Wocao](https://attack.mitre.org/campaigns/C0014), threat actors used [PowerSploit](https://attack.mitre.org/software/S0194)'s `Invoke-Kerberoast` module to request encrypted service tickets and bruteforce the passwords of Windows service accounts offline.(Citation: FoxIT Wocao December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--827cbddc-3e19-4aff-a27a-5cce63812d44`.
