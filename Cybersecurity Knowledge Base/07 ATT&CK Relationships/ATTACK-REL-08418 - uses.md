---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1051"
target_object: "T1573.002"
stix_relationship_id: "relationship--ba9380c1-1d2e-4161-8c46-9fc9f793cbd3"
---
# Relationship 8418: S1051 — uses → T1573.002

**Source object:** [[01 ATT&CK/S1051 - KEYPLUG|S1051: KEYPLUG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1573.002 - Asymmetric Cryptography|T1573.002: Asymmetric Cryptography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KEYPLUG](https://attack.mitre.org/software/S1051) can use TLS-encrypted WebSocket Protocol (WSS) for C2.(Citation: Mandiant APT41)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba9380c1-1d2e-4161-8c46-9fc9f793cbd3`.
