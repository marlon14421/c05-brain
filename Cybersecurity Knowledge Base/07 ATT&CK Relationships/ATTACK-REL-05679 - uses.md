---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1148"
target_object: "T1033"
stix_relationship_id: "relationship--1deaad9b-3a33-421b-b13b-6dcad02707cf"
---
# Relationship 5679: S1148 — uses → T1033

**Source object:** [[01 ATT&CK/S1148 - Raccoon Stealer|S1148: Raccoon Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Raccoon Stealer](https://attack.mitre.org/software/S1148) gathers information on the infected system owner and user.(Citation: S2W Racoon 2022)(Citation: Sekoia Raccoon1 2022)(Citation: Sekoia Raccoon2 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1deaad9b-3a33-421b-b13b-6dcad02707cf`.
