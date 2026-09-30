---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0036"
target_object: "T1059.001"
stix_relationship_id: "relationship--dd584826-35e3-4c6f-8186-b5f5a9ea5229"
---
# Relationship 2766: C0036 — uses → T1059.001

**Source object:** [[01 ATT&CK/C0036 - Pikabot Distribution February 2024|C0036: Pikabot Distribution February 2024]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Pikabot Distribution February 2024](https://attack.mitre.org/campaigns/C0036) passed execution from obfuscated JavaScript files to PowerShell scripts to download and install [Pikabot](https://attack.mitre.org/software/S1145).(Citation: Elastic Pikabot 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd584826-35e3-4c6f-8186-b5f5a9ea5229`.
