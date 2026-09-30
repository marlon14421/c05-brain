---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0090"
target_object: "T1083"
stix_relationship_id: "relationship--e90717f3-fad2-4978-be15-7dfb647d034d"
---
# Relationship 7111: S0090 — uses → T1083

**Source object:** [[01 ATT&CK/S0090 - Rover|S0090: Rover]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1083 - File and Directory Discovery|T1083: File and Directory Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Rover](https://attack.mitre.org/software/S0090) automatically searches for files on local drives based on a predefined list of file extensions.(Citation: Palo Alto Rover)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e90717f3-fad2-4978-be15-7dfb647d034d`.
