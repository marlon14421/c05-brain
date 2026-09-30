---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0334"
target_object: "T1056.001"
stix_relationship_id: "relationship--da288184-6537-4a23-b26e-e4329690bddb"
---
# Relationship 7764: S0334 — uses → T1056.001

**Source object:** [[01 ATT&CK/S0334 - DarkComet|S0334: DarkComet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1056.001 - Keylogging|T1056.001: Keylogging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkComet](https://attack.mitre.org/software/S0334) has a keylogging capability.(Citation: TrendMicro DarkComet Sept 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--da288184-6537-4a23-b26e-e4329690bddb`.
