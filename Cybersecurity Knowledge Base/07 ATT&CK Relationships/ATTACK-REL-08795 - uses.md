---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1119"
target_object: "T1573.001"
stix_relationship_id: "relationship--5bef15c2-1aa4-4f94-b594-0b5e03c26a41"
---
# Relationship 8795: S1119 — uses → T1573.001

**Source object:** [[01 ATT&CK/S1119 - LIGHTWIRE|S1119: LIGHTWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LIGHTWIRE](https://attack.mitre.org/software/S1119) can RC4 encrypt C2 commands.(Citation: Mandiant Cutting Edge Part 2 January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5bef15c2-1aa4-4f94-b594-0b5e03c26a41`.
