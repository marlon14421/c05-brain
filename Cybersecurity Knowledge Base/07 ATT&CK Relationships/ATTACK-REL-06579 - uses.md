---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9026"
target_object: "T1047"
stix_relationship_id: "relationship--b67e0e26-717f-4aab-871c-22d9bfddc5d1"
---
# Relationship 6579: S9026 — uses → T1047

**Source object:** [[01 ATT&CK/S9026 - ROAMINGHOUSE|S9026: ROAMINGHOUSE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROAMINGHOUSE](https://attack.mitre.org/software/S9026) can use WMI to launch a legitimate executable later used to enable DLL sideloading.(Citation: Trend Micro Earth Kasha Updates APR 2025)(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b67e0e26-717f-4aab-871c-22d9bfddc5d1`.
