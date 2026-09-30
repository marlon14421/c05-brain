---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1081"
target_object: "T1573.002"
stix_relationship_id: "relationship--922d5db0-2588-46d9-9a91-e5d4ccc3c84c"
---
# Relationship 6426: S1081 — uses → T1573.002

**Source object:** [[01 ATT&CK/S1081 - BADHATCH|S1081: BADHATCH]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BADHATCH](https://attack.mitre.org/software/S1081) can beacon to a hardcoded C2 IP address using TLS encryption every 5 minutes.(Citation: Gigamon BADHATCH Jul 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--922d5db0-2588-46d9-9a91-e5d4ccc3c84c`.
