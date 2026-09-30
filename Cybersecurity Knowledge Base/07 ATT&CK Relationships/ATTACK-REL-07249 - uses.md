---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0579"
target_object: "T1049"
stix_relationship_id: "relationship--88d6a08e-2e96-41de-868f-b41c07d11541"
---
# Relationship 7249: S0579 — uses → T1049

**Source object:** [[01 ATT&CK/S0579 - Waterbear|S0579: Waterbear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1049 - System Network Connections Discovery|T1049: System Network Connections Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Waterbear](https://attack.mitre.org/software/S0579) can use API hooks on `GetExtendedTcpTable` to retrieve a table containing a list of TCP endpoints available to the application.(Citation: Trend Micro Waterbear December 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--88d6a08e-2e96-41de-868f-b41c07d11541`.
