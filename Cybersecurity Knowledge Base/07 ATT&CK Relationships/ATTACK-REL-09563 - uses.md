---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0627"
target_object: "T1012"
stix_relationship_id: "relationship--e9a4e4bd-717a-4048-a623-4a1758b93acd"
---
# Relationship 9563: S0627 — uses → T1012

**Source object:** [[01 ATT&CK/S0627 - SodaMaster|S0627: SodaMaster]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SodaMaster](https://attack.mitre.org/software/S0627) has the ability to query the Registry to detect a key specific to VMware.(Citation: Securelist APT10 March 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e9a4e4bd-717a-4048-a623-4a1758b93acd`.
