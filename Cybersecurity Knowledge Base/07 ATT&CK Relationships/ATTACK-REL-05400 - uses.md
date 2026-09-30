---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0554"
target_object: "T1082"
stix_relationship_id: "relationship--f0a74237-9a46-4ea8-a268-3ac87f593ea9"
---
# Relationship 5400: S0554 — uses → T1082

**Source object:** [[01 ATT&CK/S0554 - Egregor|S0554: Egregor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Egregor](https://attack.mitre.org/software/S0554) can perform a language check of the infected system and can query the CPU information (cupid).(Citation: JoeSecurity Egregor 2020)(Citation: NHS Digital Egregor Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f0a74237-9a46-4ea8-a268-3ac87f593ea9`.
