---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0441"
target_object: "T1560.001"
stix_relationship_id: "relationship--dd82b9d7-d60c-4dc0-97d7-244a1365a1e9"
---
# Relationship 2694: S0441 — uses → T1560.001

**Source object:** [[01 ATT&CK/S0441 - PowerShower|S0441: PowerShower]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.001 - Archive via Utility|T1560.001: Archive via Utility]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[PowerShower](https://attack.mitre.org/software/S0441) has used 7Zip to compress .txt, .pdf, .xls or .doc files prior to exfiltration.(Citation: Kaspersky Cloud Atlas August 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd82b9d7-d60c-4dc0-97d7-244a1365a1e9`.
