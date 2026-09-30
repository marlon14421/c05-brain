---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0037"
target_object: "T1059.001"
stix_relationship_id: "relationship--97ea3b82-58ba-4a3e-8e6d-367755f83fa6"
---
# Relationship 3557: G0037 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0037 - FIN6|G0037: FIN6]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[FIN6](https://attack.mitre.org/groups/G0037) has used PowerShell to gain access to merchant's networks, and a Metasploit PowerShell module to download and execute shellcode and to set up a local listener.(Citation: FireEye FIN6 April 2016)(Citation: FireEye FIN6 Apr 2019)(Citation: Visa FIN6 Feb 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--97ea3b82-58ba-4a3e-8e6d-367755f83fa6`.
