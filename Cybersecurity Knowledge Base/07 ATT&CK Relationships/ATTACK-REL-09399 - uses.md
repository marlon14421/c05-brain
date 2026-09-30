---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0611"
target_object: "T1614.001"
stix_relationship_id: "relationship--7a64941e-c585-4ded-b0d7-2d7f3d71eaa8"
---
# Relationship 9399: S0611 — uses → T1614.001

**Source object:** [[01 ATT&CK/S0611 - Clop|S0611: Clop]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1614.001 - System Language Discovery|T1614.001: System Language Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clop](https://attack.mitre.org/software/S0611) has checked the keyboard language using the GetKeyboardLayout() function to avoid installation on Russian-language or other Commonwealth of Independent States-language machines; it will also check the GetTextCharset function.(Citation: Mcafee Clop Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7a64941e-c585-4ded-b0d7-2d7f3d71eaa8`.
