---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0520"
target_object: "T1036.005"
stix_relationship_id: "relationship--44577477-b599-46f0-84bf-7e0de773d848"
---
# Relationship 7972: S0520 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0520 - BLINDINGCAN|S0520: BLINDINGCAN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BLINDINGCAN](https://attack.mitre.org/software/S0520) has attempted to hide its payload by using legitimate file names such as "iconcache.db".(Citation: US-CERT BLINDINGCAN Aug 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--44577477-b599-46f0-84bf-7e0de773d848`.
