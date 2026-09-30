---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0081"
target_object: "T1027.013"
stix_relationship_id: "relationship--68bbad6c-1685-4275-bd36-b885a64caf6d"
---
# Relationship 8982: S0081 — uses → T1027.013

**Source object:** [[01 ATT&CK/S0081 - Elise|S0081: Elise]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.013 - Encrypted-Encoded File|T1027.013: Encrypted/Encoded File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Elise](https://attack.mitre.org/software/S0081) encrypts several of its files, including configuration files.(Citation: Lotus Blossom Jun 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--68bbad6c-1685-4275-bd36-b885a64caf6d`.
