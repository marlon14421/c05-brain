---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1249"
target_object: "T1059.007"
stix_relationship_id: "relationship--65dfb984-a7b3-4da0-90d0-20d61eb0e828"
---
# Relationship 8486: S1249 — uses → T1059.007

**Source object:** [[01 ATT&CK/S1249 - HexEval Loader|S1249: HexEval Loader]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.007 - JavaScript|T1059.007: JavaScript]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HexEval Loader](https://attack.mitre.org/software/S1249) has executed malicious JavaScript code.(Citation: Socket Contagious Interview NPM April 2025)(Citation: Socket HexEval BeaverTail Contagious Interview June 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--65dfb984-a7b3-4da0-90d0-20d61eb0e828`.
