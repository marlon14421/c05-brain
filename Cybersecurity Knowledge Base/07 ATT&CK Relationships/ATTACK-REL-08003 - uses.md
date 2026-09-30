---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0144"
target_object: "T1573.001"
stix_relationship_id: "relationship--e376d1ed-a35a-47c1-98c6-4d37f52b1b84"
---
# Relationship 8003: S0144 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0144 - ChChes|S0144: ChChes]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ChChes](https://attack.mitre.org/software/S0144) can encrypt C2 traffic with AES or RC4.(Citation: Palo Alto menuPass Feb 2017)(Citation: JPCERT ChChes Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e376d1ed-a35a-47c1-98c6-4d37f52b1b84`.
