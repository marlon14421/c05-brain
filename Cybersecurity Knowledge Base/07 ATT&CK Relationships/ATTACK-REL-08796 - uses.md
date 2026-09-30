---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0628"
target_object: "T1083"
stix_relationship_id: "relationship--807b9e89-a895-4c9b-aace-1d1ced5824b9"
---
# Relationship 8796: S0628 — uses → T1083

**Source object:** [[01 ATT&CK/S0628 - FYAnti|S0628: FYAnti]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FYAnti](https://attack.mitre.org/software/S0628) can search the C:\Windows\Microsoft.NET\ directory for files of a specified size.(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--807b9e89-a895-4c9b-aace-1d1ced5824b9`.
