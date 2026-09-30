---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1573.001"
stix_relationship_id: "relationship--71bb09bc-0405-43ed-9848-bf685234c670"
---
# Relationship 6015: S0266 — uses → T1573.001

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.001 - Symmetric Cryptography|T1573.001: Symmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) uses a custom crypter leveraging Microsoft’s CryptoAPI to encrypt C2 traffic.(Citation: Fidelis TrickBot Oct 2016)Newer versions of [TrickBot](https://attack.mitre.org/software/S0266) have been known to use `bcrypt` to encrypt and digitally sign responses to their C2 server. (Citation: Bitdefender Trickbot C2 infra Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--71bb09bc-0405-43ed-9848-bf685234c670`.
