---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9022"
target_object: "T1555.003"
stix_relationship_id: "relationship--976118d5-b033-4dfc-b4be-b8190f2cf641"
---
# Relationship 7753: S9022 — uses → T1555.003

**Source object:** [[01 ATT&CK/S9022 - MirrorStealer|S9022: MirrorStealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MirrorStealer](https://attack.mitre.org/software/S9022) can steal credentials stored in browsers.(Citation: ESET MirrorFace DEC 2022)(Citation: Trend Micro Earth Kasha NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--976118d5-b033-4dfc-b4be-b8190f2cf641`.
