---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1059.001"
stix_relationship_id: "relationship--73baa214-fbe6-477e-9beb-d1a08a6d117f"
---
# Relationship 3844: G0102 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used macros to execute PowerShell scripts to download malware on victim's machines.(Citation: CrowdStrike Grim Spider May 2019) It has also used PowerShell to execute commands and move laterally through a victim network.(Citation: DHS/CISA Ransomware Targeting Healthcare October 2020)(Citation: FireEye KEGTAP SINGLEMALT October 2020)(Citation: Red Canary Hospital Thwarted Ryuk October 2020)(Citation: Mandiant FIN12 Oct 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73baa214-fbe6-477e-9beb-d1a08a6d117f`.
