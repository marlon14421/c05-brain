---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1148"
target_object: "T1020"
stix_relationship_id: "relationship--72513bb1-7e36-415f-a6bd-4b1a908509ef"
---
# Relationship 3190: S1148 — uses → T1020

**Source object:** [[01 ATT&CK/S1148 - Raccoon Stealer|S1148: Raccoon Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1020 - Automated Exfiltration|T1020: Automated Exfiltration]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Raccoon Stealer](https://attack.mitre.org/software/S1148) will automatically collect and exfiltrate data identified in received configuration files from command and control nodes.(Citation: S2W Racoon 2022)(Citation: Sekoia Raccoon1 2022)(Citation: Sekoia Raccoon2 2022)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--72513bb1-7e36-415f-a6bd-4b1a908509ef`.
