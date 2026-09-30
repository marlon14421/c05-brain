---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0039"
target_object: "T1069.001"
stix_relationship_id: "relationship--75f7d0e0-b1e9-4289-8895-d8a262930523"
---
# Relationship 7721: S0039 — uses → T1069.001

**Source object:** [[01 ATT&CK/S0039 - Net|S0039: Net]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1069.001 - Local Groups|T1069.001: Local Groups]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Commands such as net group and net localgroup can be used in [Net](https://attack.mitre.org/software/S0039) to gather information about and manipulate groups.(Citation: Savill 1999)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--75f7d0e0-b1e9-4289-8895-d8a262930523`.
