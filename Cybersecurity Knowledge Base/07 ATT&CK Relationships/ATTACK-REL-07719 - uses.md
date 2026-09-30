---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0018"
target_object: "T1486"
stix_relationship_id: "relationship--6cfee0a9-4f55-42e9-8670-86a0fa3e6280"
---
# Relationship 7719: C0018 — uses → T1486

**Source object:** [[01 ATT&CK/C0018 - C0018|C0018: C0018]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1486 - Data Encrypted for Impact|T1486: Data Encrypted for Impact]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During [C0018](https://attack.mitre.org/campaigns/C0018), the threat actors used [AvosLocker](https://attack.mitre.org/software/S1053) ransomware to encrypt files on the compromised network.(Citation: Cisco Talos Avos Jun 2022)(Citation: Costa AvosLocker May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cfee0a9-4f55-42e9-8670-86a0fa3e6280`.
