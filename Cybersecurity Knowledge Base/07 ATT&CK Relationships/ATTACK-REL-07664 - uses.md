---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0220"
target_object: "T1573.001"
stix_relationship_id: "relationship--25d4fa6d-4f88-4604-8b9f-cce6f3b5ae4d"
---
# Relationship 7664: S0220 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0220 - Chaos|S0220: Chaos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chaos](https://attack.mitre.org/software/S0220) provides a reverse shell connection on 8338/TCP, encrypted via AES.(Citation: Chaos Stolen Backdoor)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--25d4fa6d-4f88-4604-8b9f-cce6f3b5ae4d`.
