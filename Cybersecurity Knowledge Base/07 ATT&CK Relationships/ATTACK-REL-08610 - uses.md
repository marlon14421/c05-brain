---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0472"
target_object: "T1573.001"
stix_relationship_id: "relationship--f874b527-e973-40f2-89cb-2c7feab5b6b4"
---
# Relationship 8610: S0472 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0472 - down_new|S0472: down_new]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[down_new](https://attack.mitre.org/software/S0472) has the ability to AES encrypt C2 communications.(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f874b527-e973-40f2-89cb-2c7feab5b6b4`.
