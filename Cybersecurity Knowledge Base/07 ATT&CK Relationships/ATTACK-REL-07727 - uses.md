---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1226"
target_object: "T1115"
stix_relationship_id: "relationship--f43a1b3a-432b-47e7-8da6-4bac45d1ae4e"
---
# Relationship 7727: S1226 — uses → T1115

**Source object:** [[01 ATT&CK/S1226 - BOOKWORM|S1226: BOOKWORM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1115 - Clipboard Data|T1115: Clipboard Data]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BOOKWORM](https://attack.mitre.org/software/S1226) has used its KBLogger.dll module to steal data saved to the clipboard. (Citation: Unit42 Bookworm Nov2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f43a1b3a-432b-47e7-8da6-4bac45d1ae4e`.
