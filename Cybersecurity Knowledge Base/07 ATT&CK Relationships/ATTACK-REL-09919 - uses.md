---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9019"
target_object: "T1573.002"
stix_relationship_id: "relationship--73e1f789-978f-4ab7-be88-137d89423215"
---
# Relationship 9919: S9019 — uses → T1573.002

**Source object:** [[01 ATT&CK/S9019 - PureCrypter|S9019: PureCrypter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PureCrypter](https://attack.mitre.org/software/S9019) can send a TLS 1.2 encrypted infection message via Discord webhook.(Citation: Zscaler PureCrypter JUN 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--73e1f789-978f-4ab7-be88-137d89423215`.
