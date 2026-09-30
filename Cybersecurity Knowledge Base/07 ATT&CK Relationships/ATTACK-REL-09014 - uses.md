---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0387"
target_object: "T1016"
stix_relationship_id: "relationship--0aafbc63-2021-4c99-b273-1241943fd959"
---
# Relationship 9014: S0387 — uses → T1016

**Source object:** [[01 ATT&CK/S0387 - KeyBoy|S0387: KeyBoy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1016 - System Network Configuration Discovery|T1016: System Network Configuration Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[KeyBoy](https://attack.mitre.org/software/S0387) can determine the public or WAN IP address for the system.(Citation: PWC KeyBoys Feb 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--0aafbc63-2021-4c99-b273-1241943fd959`.
