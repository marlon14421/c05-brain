---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0546"
target_object: "T1047"
stix_relationship_id: "relationship--dcd99f6a-c554-4b04-a962-dc3a5f89cdf9"
---
# Relationship 6168: S0546 — uses → T1047

**Source object:** [[01 ATT&CK/S0546 - SharpStage|S0546: SharpStage]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SharpStage](https://attack.mitre.org/software/S0546) can use WMI for execution.(Citation: Cybereason Molerats Dec 2020)(Citation: BleepingComputer Molerats Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dcd99f6a-c554-4b04-a962-dc3a5f89cdf9`.
