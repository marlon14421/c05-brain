---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1121"
target_object: "T1090"
stix_relationship_id: "relationship--41fd4cc5-8d62-43f6-833b-1068a8f3003c"
---
# Relationship 8174: S1121 — uses → T1090

**Source object:** [[01 ATT&CK/S1121 - LITTLELAMB.WOOLTEA|S1121: LITTLELAMB.WOOLTEA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LITTLELAMB.WOOLTEA](https://attack.mitre.org/software/S1121) has the ability to function as a SOCKS proxy.(Citation: Mandiant Cutting Edge Part 3 February 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41fd4cc5-8d62-43f6-833b-1068a8f3003c`.
