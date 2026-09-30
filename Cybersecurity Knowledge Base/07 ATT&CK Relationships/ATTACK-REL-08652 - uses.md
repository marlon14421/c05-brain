---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1016"
target_object: "T1082"
stix_relationship_id: "relationship--3114ebc8-7dc2-4ee7-8aad-5b764f27a6d8"
---
# Relationship 8652: G1016 — uses → T1082

**Source object:** [[01 ATT&CK/G1016 - FIN13|G1016: FIN13]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN13](https://attack.mitre.org/groups/G1016) has collected local host information by utilizing Windows commands `systeminfo`, `fsutil`, and `fsinfo`. [FIN13](https://attack.mitre.org/groups/G1016) has also utilized a compromised Symantex Altiris console and LanDesk account to retrieve host information.(Citation: Mandiant FIN13 Aug 2022)(Citation: Sygnia Elephant Beetle Jan 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3114ebc8-7dc2-4ee7-8aad-5b764f27a6d8`.
