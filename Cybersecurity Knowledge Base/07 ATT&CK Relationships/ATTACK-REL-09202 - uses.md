---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0513"
target_object: "T1033"
stix_relationship_id: "relationship--d54e7a92-0601-4b77-8675-46e33b577b4d"
---
# Relationship 9202: S0513 — uses → T1033

**Source object:** [[01 ATT&CK/S0513 - LiteDuke|S0513: LiteDuke]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LiteDuke](https://attack.mitre.org/software/S0513) can enumerate the account name on a targeted system.(Citation: ESET Dukes October 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d54e7a92-0601-4b77-8675-46e33b577b4d`.
