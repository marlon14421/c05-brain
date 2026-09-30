---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0186"
target_object: "T1033"
stix_relationship_id: "relationship--6cf42ee6-a064-4d8a-99d4-8aa0f878ae2a"
---
# Relationship 9527: S0186 — uses → T1033

**Source object:** [[01 ATT&CK/S0186 - DownPaper|S0186: DownPaper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DownPaper](https://attack.mitre.org/software/S0186) collects the victim username and sends it to the C2 server.(Citation: ClearSky Charming Kitten Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6cf42ee6-a064-4d8a-99d4-8aa0f878ae2a`.
