---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0171"
target_object: "T1573.001"
stix_relationship_id: "relationship--fa035513-59b6-4f54-8b85-13ec08849453"
---
# Relationship 9251: S0171 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0171 - Felismus|S0171: Felismus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Some [Felismus](https://attack.mitre.org/software/S0171) samples use a custom encryption method for C2 traffic that utilizes AES and multiple keys.(Citation: Forcepoint Felismus Mar 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fa035513-59b6-4f54-8b85-13ec08849453`.
