---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1047"
stix_relationship_id: "relationship--088f896a-59a4-4bce-aacf-3a1f0d6c4237"
---
# Relationship 8207: S0559 — uses → T1047

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) used the WMI query Select * From Win32_SystemDriver to retrieve a driver listing.(Citation: FireEye SUNBURST Backdoor December 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--088f896a-59a4-4bce-aacf-3a1f0d6c4237`.
