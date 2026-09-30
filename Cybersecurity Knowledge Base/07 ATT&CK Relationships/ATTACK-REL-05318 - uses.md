---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0358"
target_object: "T1137.004"
stix_relationship_id: "relationship--af415c7f-b7aa-4a9e-b1a8-ae09d67070de"
---
# Relationship 5318: S0358 — uses → T1137.004

**Source object:** [[01 ATT&CK/S0358 - Ruler|S0358: Ruler]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1137.004 - Outlook Home Page|T1137.004: Outlook Home Page]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ruler](https://attack.mitre.org/software/S0358) can be used to automate the abuse of Outlook Home Pages to establish persistence.(Citation: SensePost Ruler GitHub)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--af415c7f-b7aa-4a9e-b1a8-ae09d67070de`.
