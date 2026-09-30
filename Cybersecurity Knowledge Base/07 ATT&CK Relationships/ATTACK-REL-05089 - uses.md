---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0398"
target_object: "T1007"
stix_relationship_id: "relationship--7e42e286-af96-4178-a30f-785ed3699659"
---
# Relationship 5089: S0398 — uses → T1007

**Source object:** [[01 ATT&CK/S0398 - HyperBro|S0398: HyperBro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HyperBro](https://attack.mitre.org/software/S0398) can list all services and their configurations.(Citation: Unit42 Emissary Panda May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7e42e286-af96-4178-a30f-785ed3699659`.
