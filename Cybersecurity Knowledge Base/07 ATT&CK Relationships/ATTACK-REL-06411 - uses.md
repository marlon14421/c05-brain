---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1032"
target_object: "T1537"
stix_relationship_id: "relationship--463d6149-8561-4e11-a5a7-c24faa34da62"
---
# Relationship 6411: G1032 — uses → T1537

**Source object:** [[01 ATT&CK/G1032 - INC Ransom|G1032: INC Ransom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1537 - Transfer Data to Cloud Account|T1537: Transfer Data to Cloud Account]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[INC Ransom](https://attack.mitre.org/groups/G1032) has used Megasync to exfiltrate data to the cloud.(Citation: Secureworks GOLD IONIC April 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--463d6149-8561-4e11-a5a7-c24faa34da62`.
