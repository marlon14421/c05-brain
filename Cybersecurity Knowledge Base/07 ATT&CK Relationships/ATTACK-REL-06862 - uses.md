---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9010"
target_object: "T1518"
stix_relationship_id: "relationship--cb72e7c8-23a4-40d8-916e-99a18db9039c"
---
# Relationship 6862: S9010 — uses → T1518

**Source object:** [[01 ATT&CK/S9010 - GlassWorm|S9010: GlassWorm]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GlassWorm](https://attack.mitre.org/software/S9010) has searched for existing wallet applications to include Ledger Live and Trezor Suite.(Citation: Koi Glassworm New Tricks December 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cb72e7c8-23a4-40d8-916e-99a18db9039c`.
