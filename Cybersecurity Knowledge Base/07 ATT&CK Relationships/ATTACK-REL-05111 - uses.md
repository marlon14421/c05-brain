---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0138"
target_object: "T1071.003"
stix_relationship_id: "relationship--6e2a0844-3618-41a7-b45d-12ad690f60a1"
---
# Relationship 5111: S0138 — uses → T1071.003

**Source object:** [[01 ATT&CK/S0138 - OLDBAIT|S0138: OLDBAIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.003 - Mail Protocols|T1071.003: Mail Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OLDBAIT](https://attack.mitre.org/software/S0138) can use SMTP for C2.(Citation: FireEye APT28)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--6e2a0844-3618-41a7-b45d-12ad690f60a1`.
