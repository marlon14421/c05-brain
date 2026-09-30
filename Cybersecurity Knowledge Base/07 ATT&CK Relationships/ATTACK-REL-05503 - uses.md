---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0386"
target_object: "T1185"
stix_relationship_id: "relationship--eafddae6-8e14-491b-82af-40ddaccb99c6"
---
# Relationship 5503: S0386 — uses → T1185

**Source object:** [[01 ATT&CK/S0386 - Ursnif|S0386: Ursnif]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1185 - Browser Session Hijacking|T1185: Browser Session Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ursnif](https://attack.mitre.org/software/S0386) has injected HTML codes into banking sites to steal sensitive online banking information (ex: usernames and passwords).(Citation: TrendMicro BKDR_URSNIF.SM)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eafddae6-8e14-491b-82af-40ddaccb99c6`.
