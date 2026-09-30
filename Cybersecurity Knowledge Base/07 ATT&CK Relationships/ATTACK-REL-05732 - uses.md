---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1085"
target_object: "T1620"
stix_relationship_id: "relationship--cd85bffe-6371-4fd9-b327-469647ebb420"
---
# Relationship 5732: S1085 — uses → T1620

**Source object:** [[01 ATT&CK/S1085 - Sardonic|S1085: Sardonic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1620 - Reflective Code Loading|T1620: Reflective Code Loading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sardonic](https://attack.mitre.org/software/S1085) has a plugin system that can load specially made DLLs into memory and execute their functions.(Citation: Bitdefender Sardonic Aug 2021)(Citation: Symantec FIN8 Jul 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cd85bffe-6371-4fd9-b327-469647ebb420`.
