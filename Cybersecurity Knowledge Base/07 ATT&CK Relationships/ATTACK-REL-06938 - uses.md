---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1014"
target_object: "T1071.001"
stix_relationship_id: "relationship--79d38aef-d99a-4abc-a643-c334e41173f7"
---
# Relationship 6938: S1014 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1014 - DanBot|S1014: DanBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DanBot](https://attack.mitre.org/software/S1014) can use HTTP in C2 communication.(Citation: SecureWorks August 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--79d38aef-d99a-4abc-a643-c334e41173f7`.
