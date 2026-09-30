---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0083"
target_object: "T1083"
stix_relationship_id: "relationship--1a4c94a1-6362-42b3-b1d9-41ae3fbf5ea5"
---
# Relationship 5349: S0083 — uses → T1083

**Source object:** [[01 ATT&CK/S0083 - Misdat|S0083: Misdat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Misdat](https://attack.mitre.org/software/S0083) is capable of running commands to obtain a list of files and directories, as well as enumerating logical drives.(Citation: Cylance Dust Storm)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1a4c94a1-6362-42b3-b1d9-41ae3fbf5ea5`.
