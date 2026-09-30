---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0151"
target_object: "T1082"
stix_relationship_id: "relationship--d6154157-fe69-4da3-8cc3-790eecf33f8c"
---
# Relationship 9045: S0151 — uses → T1082

**Source object:** [[01 ATT&CK/S0151 - HALFBAKED|S0151: HALFBAKED]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HALFBAKED](https://attack.mitre.org/software/S0151) can obtain information about the OS, processor, and BIOS.(Citation: FireEye FIN7 April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d6154157-fe69-4da3-8cc3-790eecf33f8c`.
