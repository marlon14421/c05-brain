---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1082"
stix_relationship_id: "relationship--b5076cf3-ccd5-4dd7-895b-abf79eddf63f"
---
# Relationship 5553: S9010 — uses → T1082

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has the ability to check the OS of the victim host.(Citation: Socket GlassWorm January 2026)(Citation: Koi GlassWorm Rust December 2025) [GlassWorm](https://attack.mitre.org/software/S9010) has checked whether the OS platform value includes `darwin` prior to execution of macOS specific scripts.(Citation: Socket GlassWorm January 2026)(Citation: Koi GlassWorm Rust December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b5076cf3-ccd5-4dd7-895b-abf79eddf63f`.
