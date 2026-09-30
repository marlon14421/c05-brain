---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1226"
target_object: "T1564.003"
stix_relationship_id: "relationship--74a577af-ef40-4767-a80a-68222fff5126"
---
# Relationship 5193: S1226 — uses → T1564.003

**Source object:** [[01 ATT&CK/S1226 - BOOKWORM|S1226: BOOKWORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.003 - Hidden Window|T1564.003: Hidden Window]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOOKWORM](https://attack.mitre.org/software/S1226) has created a hidden window when conducting key logging and clipboard theft through its KBLogger.dll module.(Citation: Unit42 Bookworm Nov2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--74a577af-ef40-4767-a80a-68222fff5126`.
