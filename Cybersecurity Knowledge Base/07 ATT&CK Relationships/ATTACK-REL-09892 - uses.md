---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0186"
target_object: "T1082"
stix_relationship_id: "relationship--396edbf6-41b5-4377-90b6-4967c24de7fb"
---
# Relationship 9892: S0186 — uses → T1082

**Source object:** [[01 ATT&CK/S0186 - DownPaper|S0186: DownPaper]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DownPaper](https://attack.mitre.org/software/S0186) collects the victim host name and serial number, and then sends the information to the C2 server.(Citation: ClearSky Charming Kitten Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--396edbf6-41b5-4377-90b6-4967c24de7fb`.
