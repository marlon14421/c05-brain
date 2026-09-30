---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0498"
target_object: "T1095"
stix_relationship_id: "relationship--dd2c9cb1-9c5a-4c97-83e4-4beee309a7cb"
---
# Relationship 5280: S0498 — uses → T1095

**Source object:** [[01 ATT&CK/S0498 - Cryptoistic|S0498: Cryptoistic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1095 - Non-Application Layer Protocol|T1095: Non-Application Layer Protocol]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cryptoistic](https://attack.mitre.org/software/S0498) can use TCP in communications with C2.(Citation: SentinelOne Lazarus macOS July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dd2c9cb1-9c5a-4c97-83e4-4beee309a7cb`.
