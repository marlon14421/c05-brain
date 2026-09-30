---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0060"
target_object: "T1071.001"
stix_relationship_id: "relationship--c80250a5-79c0-4a46-a0e3-49d6bcd574c6"
---
# Relationship 6348: S0060 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0060 - Sys10|S0060: Sys10]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Sys10](https://attack.mitre.org/software/S0060) uses HTTP for C2.(Citation: Baumgartner Naikon 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c80250a5-79c0-4a46-a0e3-49d6bcd574c6`.
