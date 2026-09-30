---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0047"
target_object: "T1082"
stix_relationship_id: "relationship--36112f24-7814-4c75-b5b7-a1205bb28b68"
---
# Relationship 5049: G0047 — uses → T1082

**Source object:** [[01 ATT&CK/G0047 - Gamaredon Group|G0047: Gamaredon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [Gamaredon Group](https://attack.mitre.org/groups/G0047) file stealer can gather the victim's computer name and drive serial numbers to send to a C2 server.(Citation: Palo Alto Gamaredon Feb 2017)(Citation: TrendMicro Gamaredon April 2020)(Citation: CERT-EE Gamaredon January 2021)(Citation: SymantecCarbonBlack_ShuckwormUSB_Apr2025)(Citation: ESET Gamaredon Sept2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36112f24-7814-4c75-b5b7-a1205bb28b68`.
