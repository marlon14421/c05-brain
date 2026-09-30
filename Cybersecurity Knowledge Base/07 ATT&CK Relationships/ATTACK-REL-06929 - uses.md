---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0284"
target_object: "T1573.001"
stix_relationship_id: "relationship--2b454322-5ad5-449f-86c9-092867acd51c"
---
# Relationship 6929: S0284 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0284 - More_eggs|S0284: More_eggs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[More_eggs](https://attack.mitre.org/software/S0284) has used an RC4-based encryption method for its C2 communications.(Citation: Security Intelligence More Eggs Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2b454322-5ad5-449f-86c9-092867acd51c`.
