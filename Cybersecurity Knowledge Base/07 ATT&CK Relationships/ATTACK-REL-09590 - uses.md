---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1228"
target_object: "T1033"
stix_relationship_id: "relationship--22e70d45-8ca7-4a05-a22a-ffd5ffdd5f61"
---
# Relationship 9590: S1228 — uses → T1033

**Source object:** [[01 ATT&CK/S1228 - PUBLOAD|S1228: PUBLOAD]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PUBLOAD](https://attack.mitre.org/software/S1228) has obtained the username from an infected host.(Citation: Cisco Talos MUSTANG PANDA PLUGX PUBLOAD MAY 2022)(Citation: CSIRT CTI MUSTANG PANDA PUBLOAD TONESHELL JAN 2024)(Citation: 2025_IBM_PUBLOAD_TONESHELL_HIUPAN_CLAIMLOADER_MUSTANG PANDA)(Citation: 2022 November_TrendMicro_Earth Preta_Toneshell_Pubload)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22e70d45-8ca7-4a05-a22a-ffd5ffdd5f61`.
