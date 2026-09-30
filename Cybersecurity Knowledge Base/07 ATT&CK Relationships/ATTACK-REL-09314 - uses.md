---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0588"
target_object: "T1573.002"
stix_relationship_id: "relationship--7962fea5-a94d-4bb3-b951-fb8726bc4f67"
---
# Relationship 9314: S0588 — uses → T1573.002

**Source object:** [[01 ATT&CK/S0588 - GoldMax|S0588: GoldMax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GoldMax](https://attack.mitre.org/software/S0588) has RSA-encrypted its communication with the C2 server.(Citation: MSTIC NOBELIUM Mar 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7962fea5-a94d-4bb3-b951-fb8726bc4f67`.
