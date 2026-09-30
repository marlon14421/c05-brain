---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0057"
target_object: "T1007"
stix_relationship_id: "relationship--40c5a024-37db-478b-b90f-27f184bf8f60"
---
# Relationship 9313: S0057 — uses → T1007

**Source object:** [[01 ATT&CK/S0057 - Tasklist|S0057: Tasklist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1007 - System Service Discovery|T1007: System Service Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Tasklist](https://attack.mitre.org/software/S0057) can be used to discover services running on a system.(Citation: Microsoft Tasklist)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--40c5a024-37db-478b-b90f-27f184bf8f60`.
