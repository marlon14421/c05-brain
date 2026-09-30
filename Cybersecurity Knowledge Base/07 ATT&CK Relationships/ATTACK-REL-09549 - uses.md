---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0520"
target_object: "T1204.002"
stix_relationship_id: "relationship--a3b44434-d499-4c30-b42d-7bb0f6b4bfc4"
---
# Relationship 9549: S0520 — uses → T1204.002

**Source object:** [[01 ATT&CK/S0520 - BLINDINGCAN|S0520: BLINDINGCAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLINDINGCAN](https://attack.mitre.org/software/S0520) has lured victims into executing malicious macros embedded within Microsoft Office documents.(Citation: US-CERT BLINDINGCAN Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3b44434-d499-4c30-b42d-7bb0f6b4bfc4`.
