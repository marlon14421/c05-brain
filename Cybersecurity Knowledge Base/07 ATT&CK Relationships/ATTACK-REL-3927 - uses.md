---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0354"
target_object: "T1059.001"
stix_relationship_id: "relationship--ad825dd4-a26c-4468-8c11-91124ef9042d"
---
# Relationship 3927: S0354 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0354 - Denis|S0354: Denis]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Denis](https://attack.mitre.org/software/S0354) has a version written in PowerShell.(Citation: Cybereason Cobalt Kitty 2017)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ad825dd4-a26c-4468-8c11-91124ef9042d`.
