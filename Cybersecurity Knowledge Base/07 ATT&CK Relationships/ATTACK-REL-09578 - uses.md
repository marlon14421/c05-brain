---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1124"
target_object: "T1082"
stix_relationship_id: "relationship--1a28d78a-d11b-466a-977f-19d2e88c1952"
---
# Relationship 9578: S1124 — uses → T1082

**Source object:** [[01 ATT&CK/S1124 - SocGholish|S1124: SocGholish]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SocGholish](https://attack.mitre.org/software/S1124) has the ability to enumerate system information including the victim computer name.(Citation: SocGholish-update)(Citation: Red Canary SocGholish March 2024)(Citation: Secureworks Gold Prelude Profile)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a28d78a-d11b-466a-977f-19d2e88c1952`.
