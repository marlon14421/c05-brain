---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0334"
target_object: "T1033"
stix_relationship_id: "relationship--e96e17e7-4349-4393-b875-5bab4e8ffa5a"
---
# Relationship 6292: S0334 — uses → T1033

**Source object:** [[01 ATT&CK/S0334 - DarkComet|S0334: DarkComet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1033 - System Owner-User Discovery|T1033: System Owner/User Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkComet](https://attack.mitre.org/software/S0334) gathers the username from the victim’s machine.(Citation: TrendMicro DarkComet Sept 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e96e17e7-4349-4393-b875-5bab4e8ffa5a`.
