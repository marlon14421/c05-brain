---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0030"
target_object: "S0097"
stix_relationship_id: "relationship--3fcefdbe-87b9-4434-87ea-996425650be0"
---
# Relationship 8379: G0030 — uses → S0097

**Source object:** [[01 ATT&CK/G0030 - Lotus Blossom|G0030: Lotus Blossom]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/S0097 - Ping|S0097: Ping]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lotus Blossom](https://attack.mitre.org/groups/G0030) has used [Ping](https://attack.mitre.org/software/S0097) to verify connectivity to remote hosts.(Citation: Symantec Bilbug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3fcefdbe-87b9-4434-87ea-996425650be0`.
