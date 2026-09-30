---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0433"
target_object: "T1547.001"
stix_relationship_id: "relationship--52d12577-199c-41a6-92d6-28d26c023aea"
---
# Relationship 3340: S0433 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0433 - Rifdoor|S0433: Rifdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Rifdoor](https://attack.mitre.org/software/S0433) has created a new registry entry at HKEY_CURRENT_USERS\Software\Microsoft\Windows\CurrentVersion\Run\Graphics with a value of C:\ProgramData\Initech\Initech.exe /run .(Citation: Carbon Black HotCroissant April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--52d12577-199c-41a6-92d6-28d26c023aea`.
