---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0437"
target_object: "T1070.004"
stix_relationship_id: "relationship--0aa51def-3a75-4c69-8b65-82559d8f4c83"
---
# Relationship 8578: S0437 — uses → T1070.004

**Source object:** [[01 ATT&CK/S0437 - Kivars|S0437: Kivars]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070.004 - File Deletion|T1070.004: File Deletion]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Kivars](https://attack.mitre.org/software/S0437) has the ability to uninstall malware from the infected host.(Citation: TrendMicro BlackTech June 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0aa51def-3a75-4c69-8b65-82559d8f4c83`.
