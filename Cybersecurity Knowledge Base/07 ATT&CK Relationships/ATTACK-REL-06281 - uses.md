---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1147"
target_object: "T1016"
stix_relationship_id: "relationship--b1d3cf17-19f6-4418-8739-6909fb500e14"
---
# Relationship 6281: S1147 — uses → T1016

**Source object:** [[01 ATT&CK/S1147 - Nightdoor|S1147: Nightdoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Nightdoor](https://attack.mitre.org/software/S1147) gathers information on victim system network configuration such as MAC addresses.(Citation: ESET EvasivePanda 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--b1d3cf17-19f6-4418-8739-6909fb500e14`.
