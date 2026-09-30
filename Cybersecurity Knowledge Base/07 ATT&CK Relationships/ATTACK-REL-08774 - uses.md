---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0034"
target_object: "T1573.001"
stix_relationship_id: "relationship--122e6f20-ab3b-4bf0-bef1-0372399bee7c"
---
# Relationship 8774: S0034 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0034 - NETEAGLE|S0034: NETEAGLE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETEAGLE](https://attack.mitre.org/software/S0034) will decrypt resources it downloads with HTTP requests by using RC4 with the key "ScoutEagle."(Citation: FireEye APT30)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--122e6f20-ab3b-4bf0-bef1-0372399bee7c`.
