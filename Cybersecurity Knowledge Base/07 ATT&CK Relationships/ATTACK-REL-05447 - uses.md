---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9030"
target_object: "T1614"
stix_relationship_id: "relationship--5dd07f94-a3bf-48a3-ad5b-888f5b2953b4"
---
# Relationship 5447: S9030 — uses → T1614

**Source object:** [[01 ATT&CK/S9030 - SameCoin|S9030: SameCoin]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614 - System Location Discovery|T1614: System Location Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SameCoin](https://attack.mitre.org/software/S9030) can attempt to connect to the Israel Home Front Command site, oref.org[.]il, which is only reachable from within Israel to verify the target's location.(Citation: Check Point Wirte NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5dd07f94-a3bf-48a3-ad5b-888f5b2953b4`.
