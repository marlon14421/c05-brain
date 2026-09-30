---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0340"
target_object: "T1680"
stix_relationship_id: "relationship--c8a336f0-300c-4c9a-a501-5d679f583048"
---
# Relationship 7934: S0340 — uses → T1680

**Source object:** [[01 ATT&CK/S0340 - Octopus|S0340: Octopus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1680 - Local Storage Discovery|T1680: Local Storage Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Octopus](https://attack.mitre.org/software/S0340) can collect system drive and disk size information.(Citation: Securelist Octopus Oct 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c8a336f0-300c-4c9a-a501-5d679f583048`.
