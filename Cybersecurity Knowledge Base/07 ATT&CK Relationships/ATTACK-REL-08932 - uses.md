---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0015"
target_object: "T1083"
stix_relationship_id: "relationship--b7999bd1-4704-489d-8fc3-80661592b6dc"
---
# Relationship 8932: S0015 — uses → T1083

**Source object:** [[01 ATT&CK/S0015 - Ixeshe|S0015: Ixeshe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ixeshe](https://attack.mitre.org/software/S0015) can list file and directory information.(Citation: Trend Micro IXESHE 2012)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b7999bd1-4704-489d-8fc3-80661592b6dc`.
