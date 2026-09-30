---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1018"
stix_relationship_id: "relationship--df13cae2-4e20-4e89-ae60-6bd8b99e2342"
---
# Relationship 7799: G0102 — uses → T1018

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used networkdll for network discovery and psfin specifically for financial and point of sale indicators. [Wizard Spider](https://attack.mitre.org/groups/G0102) has also used [AdFind](https://attack.mitre.org/software/S0552), nltest/dclist , and PowerShell script Get-DataInfo.ps1 to enumerate domain computers, including the domain controller.(Citation: FireEye Ryuk and Trickbot January 2019)(Citation: CrowdStrike Grim Spider May 2019)(Citation: FireEye KEGTAP SINGLEMALT October 2020)(Citation: Red Canary Hospital Thwarted Ryuk October 2020)(Citation: DFIR Ryuk's Return October 2020)(Citation: Mandiant FIN12 Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--df13cae2-4e20-4e89-ae60-6bd8b99e2342`.
