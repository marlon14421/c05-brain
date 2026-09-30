---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1054"
target_object: "T1021.002"
stix_relationship_id: "relationship--ca4d13b8-73e2-4eaa-94be-952f609c422f"
---
# Relationship 9519: G1054 — uses → T1021.002

**Source object:** [[01 ATT&CK/G1054 - MirrorFace|G1054: MirrorFace]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1021.002 - SMB-Windows Admin Shares|T1021.002: SMB/Windows Admin Shares]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorFace](https://attack.mitre.org/groups/G1054) has used SMB to copy malware between systems in compromised environments.(Citation: Trend Micro Earth Kasha NOV 2024)(Citation: JPCERT MirrorFace JUL 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca4d13b8-73e2-4eaa-94be-952f609c422f`.
