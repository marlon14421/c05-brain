---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1209"
target_object: "T1113"
stix_relationship_id: "relationship--67731257-6a0a-46cf-8f7e-cc6793d5fdb9"
---
# Relationship 6790: S1209 — uses → T1113

**Source object:** [[01 ATT&CK/S1209 - Quick Assist|S1209: Quick Assist]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1113 - Screen Capture|T1113: Screen Capture]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Quick Assist](https://attack.mitre.org/software/S1209) allows for the remote administrator to take screenshots of the running system.(Citation: Microsoft Quick Assist 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--67731257-6a0a-46cf-8f7e-cc6793d5fdb9`.
