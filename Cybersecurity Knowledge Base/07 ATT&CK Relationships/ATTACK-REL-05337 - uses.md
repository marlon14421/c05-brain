---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0091"
target_object: "T1083"
stix_relationship_id: "relationship--291e908e-1d2e-4b29-a564-5a33149d1dbb"
---
# Relationship 5337: S0091 — uses → T1083

**Source object:** [[01 ATT&CK/S0091 - Epic|S0091: Epic]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Epic](https://attack.mitre.org/software/S0091) recursively searches for all .doc files on the system and collects a directory listing of the Desktop, %TEMP%, and %WINDOWS%\Temp directories.(Citation: Kaspersky Turla)(Citation: Kaspersky Turla Aug 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--291e908e-1d2e-4b29-a564-5a33149d1dbb`.
