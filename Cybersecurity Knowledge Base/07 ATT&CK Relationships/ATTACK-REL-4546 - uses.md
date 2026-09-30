---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0450"
target_object: "T1027.010"
stix_relationship_id: "relationship--b5952b5f-281b-4ff4-9cfb-c2898f3028cc"
---
# Relationship 4546: S0450 — uses → T1027.010

**Source object:** [[01 ATT&CK/S0450 - SHARPSTATS|S0450: SHARPSTATS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[SHARPSTATS](https://attack.mitre.org/software/S0450) has used base64 encoding and XOR to obfuscate PowerShell scripts.(Citation: TrendMicro POWERSTATS V3 June 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5952b5f-281b-4ff4-9cfb-c2898f3028cc`.
