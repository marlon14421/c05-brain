---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1235"
target_object: "T1053.005"
stix_relationship_id: "relationship--8dafeeb9-067e-4118-9d96-ee8875711096"
---
# Relationship 6527: S1235 — uses → T1053.005

**Source object:** [[01 ATT&CK/S1235 - CorKLOG|S1235: CorKLOG]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1053.005 - Scheduled Task|T1053.005: Scheduled Task]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[CorKLOG](https://attack.mitre.org/software/S1235) has achieved persistence through the creation of a scheduled task named TableInputServices by using the command `schtasks /create /tn TabletlnputServices /tr /sc minute /mo 10 /f`.(Citation: Zscaler PAKLOG CorkLog SplatCloak Splatdropper April 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8dafeeb9-067e-4118-9d96-ee8875711096`.
