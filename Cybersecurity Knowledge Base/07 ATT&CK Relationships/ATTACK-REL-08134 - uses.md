---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1132"
target_object: "T1027.013"
stix_relationship_id: "relationship--768eb217-8d95-40aa-b697-15c426d2c99a"
---
# Relationship 8134: S1132 — uses → T1027.013

**Source object:** [[01 ATT&CK/S1132 - IPsec Helper|S1132: IPsec Helper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IPsec Helper](https://attack.mitre.org/software/S1132) contains an embedded XML configuration file with an encrypted list of command and control servers. These are written to an external configuration file during execution.(Citation: SentinelOne Agrius 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--768eb217-8d95-40aa-b697-15c426d2c99a`.
