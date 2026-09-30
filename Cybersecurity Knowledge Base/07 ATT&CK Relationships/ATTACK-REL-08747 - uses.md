---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0164"
target_object: "T1059.003"
stix_relationship_id: "relationship--ce424541-5cfa-4885-ad62-f3f70fa27099"
---
# Relationship 8747: S0164 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0164 - TDTESS|S0164: TDTESS]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TDTESS](https://attack.mitre.org/software/S0164) provides a reverse shell on the victim.(Citation: ClearSky Wilted Tulip July 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ce424541-5cfa-4885-ad62-f3f70fa27099`.
