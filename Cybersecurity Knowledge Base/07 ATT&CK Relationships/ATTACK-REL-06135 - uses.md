---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0348"
target_object: "T1083"
stix_relationship_id: "relationship--3572a770-9151-42d5-82b5-360002725052"
---
# Relationship 6135: S0348 — uses → T1083

**Source object:** [[01 ATT&CK/S0348 - Cardinal RAT|S0348: Cardinal RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cardinal RAT](https://attack.mitre.org/software/S0348) checks its current working directory upon execution and also contains watchdog functionality that ensures its executable is located in the correct path (else it will rewrite the payload).(Citation: PaloAlto CardinalRat Apr 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3572a770-9151-42d5-82b5-360002725052`.
