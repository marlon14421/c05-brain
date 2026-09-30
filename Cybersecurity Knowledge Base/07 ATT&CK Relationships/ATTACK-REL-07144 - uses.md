---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1196"
target_object: "T1217"
stix_relationship_id: "relationship--ba8ceccd-5406-418b-9f10-ed333e5f1e9c"
---
# Relationship 7144: S1196 — uses → T1217

**Source object:** [[01 ATT&CK/S1196 - Troll Stealer|S1196: Troll Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1217 - Browser Information Discovery|T1217: Browser Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Troll Stealer](https://attack.mitre.org/software/S1196) collects information from Chromium-based browsers and Firefox such as cookies, history, downloads, and extensions.(Citation: S2W Troll Stealer 2024)(Citation: Symantec Troll Stealer 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ba8ceccd-5406-418b-9f10-ed333e5f1e9c`.
