---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1027.010"
stix_relationship_id: "relationship--5a2c4561-48e4-4d51-8f00-ff470a18df32"
---
# Relationship 4824: G0102 — uses → T1027.010

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) used Base64 encoding to obfuscate an [Empire](https://attack.mitre.org/software/S0363) service and PowerShell commands.(Citation: FireEye Ryuk and Trickbot January 2019)(Citation: DFIR Ryuk's Return October 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5a2c4561-48e4-4d51-8f00-ff470a18df32`.
