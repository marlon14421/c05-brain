---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1014"
target_object: "T1547.001"
stix_relationship_id: "relationship--856db86a-62a6-4545-898f-7eb44924cfde"
---
# Relationship 9360: G1014 — uses → T1547.001

**Source object:** [[01 ATT&CK/G1014 - LuminousMoth|G1014: LuminousMoth]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LuminousMoth](https://attack.mitre.org/groups/G1014) has used malicious DLLs that setup persistence in the Registry Key `HKCU\Software\Microsoft\Windows\Current Version\Run`.(Citation: Kaspersky LuminousMoth July 2021)(Citation: Bitdefender LuminousMoth July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--856db86a-62a6-4545-898f-7eb44924cfde`.
