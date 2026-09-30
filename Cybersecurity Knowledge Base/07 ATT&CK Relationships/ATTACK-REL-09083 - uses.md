---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0262"
target_object: "T1564.003"
stix_relationship_id: "relationship--41664428-398a-4b71-9418-b1bd1e4cefc4"
---
# Relationship 9083: S0262 — uses → T1564.003

**Source object:** [[01 ATT&CK/S0262 - QuasarRAT|S0262: QuasarRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[QuasarRAT](https://attack.mitre.org/software/S0262) can hide process windows and make web requests invisible to the compromised user. Requests marked as invisible have been sent with user-agent string `Mozilla/5.0 (Macintosh; Intel Mac OS X 10_9_3) AppleWebKit/537.75.14 (KHTML, like Gecko) Version/7.0.3 Safari/7046A194A` though [QuasarRAT](https://attack.mitre.org/software/S0262) can only be run on Windows systems.(Citation: CISA AR18-352A Quasar RAT December 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--41664428-398a-4b71-9418-b1bd1e4cefc4`.
