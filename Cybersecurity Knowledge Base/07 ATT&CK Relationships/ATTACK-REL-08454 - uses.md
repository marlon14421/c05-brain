---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0034"
target_object: "T1485"
stix_relationship_id: "relationship--e85a5fe7-cbfe-44b1-b297-d02f531c5fb1"
---
# Relationship 8454: G0034 — uses → T1485

**Source object:** [[01 ATT&CK/G0034 - Sandworm Team|G0034: Sandworm Team]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1485 - Data Destruction|T1485: Data Destruction]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sandworm Team](https://attack.mitre.org/groups/G0034) has used [CaddyWiper](https://attack.mitre.org/software/S0693), [SDelete](https://attack.mitre.org/software/S0195), and the [BlackEnergy](https://attack.mitre.org/software/S0089) KillDisk component to overwrite files on victim systems. (Citation: US-CERT Ukraine Feb 2016)(Citation: ESET Telebots June 2017)(Citation: Mandiant-Sandworm-Ukraine-2022) Additionally, [Sandworm Team](https://attack.mitre.org/groups/G0034) has used the JUNKMAIL tool to overwrite files with null bytes.(Citation: mandiant_apt44_unearthing_sandworm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e85a5fe7-cbfe-44b1-b297-d02f531c5fb1`.
