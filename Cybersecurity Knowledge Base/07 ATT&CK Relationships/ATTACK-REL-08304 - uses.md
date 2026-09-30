---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1030"
target_object: "T1018"
stix_relationship_id: "relationship--22ece51b-ebfa-474d-8a6e-6835ff891890"
---
# Relationship 8304: G1030 — uses → T1018

**Source object:** [[01 ATT&CK/G1030 - Agrius|G1030: Agrius]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Agrius](https://attack.mitre.org/groups/G1030) used the tool [NBTscan](https://attack.mitre.org/software/S0590) to scan for remote, accessible hosts in victim environments.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--22ece51b-ebfa-474d-8a6e-6835ff891890`.
