---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0097"
target_object: "T1018"
stix_relationship_id: "relationship--9b2356e1-6544-40a7-a694-8ac36a1da1b7"
---
# Relationship 9217: S0097 — uses → T1018

**Source object:** [[01 ATT&CK/S0097 - Ping|S0097: Ping]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ping](https://attack.mitre.org/software/S0097) can be used to identify remote systems within a network.(Citation: TechNet Ping)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9b2356e1-6544-40a7-a694-8ac36a1da1b7`.
