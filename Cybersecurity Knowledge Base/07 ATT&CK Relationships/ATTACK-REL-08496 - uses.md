---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1024"
target_object: "T1078"
stix_relationship_id: "relationship--536ce093-85f3-4e80-9f61-4fa3739e874a"
---
# Relationship 8496: G1024 — uses → T1078

**Source object:** [[01 ATT&CK/G1024 - Akira|G1024: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1078 - Valid Accounts|T1078: Valid Accounts]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira](https://attack.mitre.org/groups/G1024) uses valid account information to remotely access victim networks, such as VPN credentials.(Citation: Secureworks GOLD SAHARA)(Citation: Arctic Wolf Akira 2023)(Citation: Cisco Akira Ransomware OCT 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--536ce093-85f3-4e80-9f61-4fa3739e874a`.
