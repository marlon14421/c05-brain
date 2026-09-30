---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0065"
target_object: "T1573.001"
stix_relationship_id: "relationship--6613ed52-5c6c-43f2-bd0c-9809769cb022"
---
# Relationship 6890: S0065 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0065 - 4H RAT|S0065: 4H RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[4H RAT](https://attack.mitre.org/software/S0065) obfuscates C2 communication using a 1-byte XOR with the key 0xBE.(Citation: CrowdStrike Putter Panda)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6613ed52-5c6c-43f2-bd0c-9809769cb022`.
