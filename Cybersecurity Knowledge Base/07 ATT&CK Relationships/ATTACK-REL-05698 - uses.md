---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0430"
target_object: "T1573.001"
stix_relationship_id: "relationship--670d65e8-59a9-46ae-bdb6-6cb94a0528ba"
---
# Relationship 5698: S0430 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0430 - Winnti for Linux|S0430: Winnti for Linux]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Winnti for Linux](https://attack.mitre.org/software/S0430) has used a custom TCP protocol with four-byte XOR for command and control (C2).(Citation: Chronicle Winnti for Linux May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--670d65e8-59a9-46ae-bdb6-6cb94a0528ba`.
