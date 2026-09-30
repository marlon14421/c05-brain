---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0568"
target_object: "T1218.010"
stix_relationship_id: "relationship--dfed3236-eb97-4a56-9325-1fb3d1c12ba4"
---
# Relationship 8322: S0568 — uses → T1218.010

**Source object:** [[01 ATT&CK/S0568 - EVILNUM|S0568: EVILNUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.010 - Regsvr32|T1218.010: Regsvr32]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EVILNUM](https://attack.mitre.org/software/S0568) can run a remote scriptlet that drops a file and executes it via regsvr32.exe.(Citation: ESET EvilNum July 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dfed3236-eb97-4a56-9325-1fb3d1c12ba4`.
