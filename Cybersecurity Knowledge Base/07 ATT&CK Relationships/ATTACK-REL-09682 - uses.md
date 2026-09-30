---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0053"
target_object: "T1190"
stix_relationship_id: "relationship--b1eac432-b174-49c1-a8bf-93cedcc7d407"
---
# Relationship 9682: C0053 — uses → T1190

**Source object:** [[01 ATT&CK/C0053 - FLORAHOX Activity|C0053: FLORAHOX Activity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FLORAHOX Activity](https://attack.mitre.org/campaigns/C0053) has exploited and infected vulnerable routers to recruit additional network devices into the ORB.(Citation: ORB Mandiant)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1eac432-b174-49c1-a8bf-93cedcc7d407`.
