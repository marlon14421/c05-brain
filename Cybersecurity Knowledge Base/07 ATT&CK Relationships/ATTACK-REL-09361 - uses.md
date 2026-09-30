---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1015"
target_object: "T1036.007"
stix_relationship_id: "relationship--eb76155e-39de-4952-857b-bf53a1586810"
---
# Relationship 9361: S1015 — uses → T1036.007

**Source object:** [[01 ATT&CK/S1015 - Milan|S1015: Milan]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.007 - Double File Extension|T1036.007: Double File Extension]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Milan](https://attack.mitre.org/software/S1015) has used an executable named `companycatalog.exe.config` to appear benign.(Citation: ClearSky Siamesekitten August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--eb76155e-39de-4952-857b-bf53a1586810`.
