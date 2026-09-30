---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1124"
target_object: "T1102"
stix_relationship_id: "relationship--f68dea79-cd44-4791-bee1-e0650868bd28"
---
# Relationship 5672: S1124 — uses → T1102

**Source object:** [[01 ATT&CK/S1124 - SocGholish|S1124: SocGholish]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1102 - Web Service|T1102: Web Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SocGholish](https://attack.mitre.org/software/S1124) has used Amazon Web Services to host second-stage servers.(Citation: SentinelOne SocGholish Infrastructure November 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f68dea79-cd44-4791-bee1-e0650868bd28`.
