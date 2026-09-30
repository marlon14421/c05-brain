---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1031"
target_object: "T1071.001"
stix_relationship_id: "relationship--39c0a771-5e52-4d08-910f-a1c9b3989f68"
---
# Relationship 5881: S1031 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1031 - PingPull|S1031: PingPull]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [PingPull](https://attack.mitre.org/software/S1031) variant can communicate with its C2 servers by using HTTPS.(Citation: Unit 42 PingPull Jun 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--39c0a771-5e52-4d08-910f-a1c9b3989f68`.
