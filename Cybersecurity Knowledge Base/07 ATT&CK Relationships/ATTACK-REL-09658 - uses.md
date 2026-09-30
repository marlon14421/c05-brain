---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1060"
target_object: "T1680"
stix_relationship_id: "relationship--a38fd59c-489b-4d3a-b3be-54fe89244c71"
---
# Relationship 9658: S1060 — uses → T1680

**Source object:** [[01 ATT&CK/S1060 - Mafalda|S1060: Mafalda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Mafalda](https://attack.mitre.org/software/S1060) can enumerate all drives on a compromised host.(Citation: SentinelLabs Metador Sept 2022)(Citation: SentinelLabs Metador Technical Appendix Sept 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a38fd59c-489b-4d3a-b3be-54fe89244c71`.
