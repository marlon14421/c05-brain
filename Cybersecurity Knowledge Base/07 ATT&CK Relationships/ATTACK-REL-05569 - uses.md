---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0198"
target_object: "T1090"
stix_relationship_id: "relationship--060a6b38-18fb-46ac-97c1-b1c40d493b6c"
---
# Relationship 5569: S0198 — uses → T1090

**Source object:** [[01 ATT&CK/S0198 - NETWIRE|S0198: NETWIRE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1090 - Proxy|T1090: Proxy]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[NETWIRE](https://attack.mitre.org/software/S0198) can implement use of proxies to pivot traffic.(Citation: Red Canary NETWIRE January 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--060a6b38-18fb-46ac-97c1-b1c40d493b6c`.
