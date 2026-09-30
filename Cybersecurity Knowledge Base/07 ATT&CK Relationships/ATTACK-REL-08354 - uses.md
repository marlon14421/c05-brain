---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1247"
target_object: "T1657"
stix_relationship_id: "relationship--155887e2-e6c3-49c3-a71d-0b2c3a8108bd"
---
# Relationship 8354: S1247 — uses → T1657

**Source object:** [[01 ATT&CK/S1247 - Embargo|S1247: Embargo]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1657 - Financial Theft|T1657: Financial Theft]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Embargo](https://attack.mitre.org/software/S1247) has been leveraged in double-extortion ransomware, exfiltrating files then encrypting them, to prompt victims to pay a ransom.(Citation: Cyble Embargo Ransomware May 2024)(Citation: ESET Embargo Ransomware October 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--155887e2-e6c3-49c3-a71d-0b2c3a8108bd`.
