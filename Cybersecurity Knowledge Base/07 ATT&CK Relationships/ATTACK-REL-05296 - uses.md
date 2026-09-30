---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1156"
target_object: "T1071.001"
stix_relationship_id: "relationship--c71e972e-cfa8-43f5-b63b-49a3afef2428"
---
# Relationship 5296: S1156 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1156 - Manjusaka|S1156: Manjusaka]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Manjusaka](https://attack.mitre.org/software/S1156) has used HTTP for command and control communication.(Citation: Talos Manjusaka 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c71e972e-cfa8-43f5-b63b-49a3afef2428`.
