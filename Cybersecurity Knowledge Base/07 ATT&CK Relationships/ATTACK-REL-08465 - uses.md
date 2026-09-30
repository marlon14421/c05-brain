---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0358"
target_object: "T1137.005"
stix_relationship_id: "relationship--066ac155-2cfd-4466-bb3a-765f3513cc8e"
---
# Relationship 8465: S0358 — uses → T1137.005

**Source object:** [[01 ATT&CK/S0358 - Ruler|S0358: Ruler]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1137.005 - Outlook Rules|T1137.005: Outlook Rules]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ruler](https://attack.mitre.org/software/S0358) can be used to automate the abuse of Outlook Rules to establish persistence.(Citation: SensePost Ruler GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--066ac155-2cfd-4466-bb3a-765f3513cc8e`.
