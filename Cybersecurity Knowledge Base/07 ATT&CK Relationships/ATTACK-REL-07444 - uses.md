---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1073"
target_object: "T1082"
stix_relationship_id: "relationship--20f43b8b-55c7-4710-8813-6512c3b11c1a"
---
# Relationship 7444: S1073 — uses → T1082

**Source object:** [[01 ATT&CK/S1073 - Royal|S1073: Royal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Royal](https://attack.mitre.org/software/S1073) can use `GetNativeSystemInfo` to enumerate system processors.(Citation: Cybereason Royal December 2022)(Citation: Trend Micro Royal Linux ESXi February 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--20f43b8b-55c7-4710-8813-6512c3b11c1a`.
