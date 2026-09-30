---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0593"
target_object: "T1027"
stix_relationship_id: "relationship--1ffbf752-ed3a-47bb-8351-92ed7118dc5d"
---
# Relationship 8212: S0593 — uses → T1027

**Source object:** [[01 ATT&CK/S0593 - ECCENTRICBANDWAGON|S0593: ECCENTRICBANDWAGON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ECCENTRICBANDWAGON](https://attack.mitre.org/software/S0593) has encrypted strings with RC4.(Citation: CISA EB Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ffbf752-ed3a-47bb-8351-92ed7118dc5d`.
