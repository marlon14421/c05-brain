---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1042"
target_object: "T1071.001"
stix_relationship_id: "relationship--d3d7c2a6-33ae-460d-a759-e3f755264d0e"
---
# Relationship 7734: S1042 — uses → T1071.001

**Source object:** [[01 ATT&CK/S1042 - SUGARDUMP|S1042: SUGARDUMP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

A [SUGARDUMP](https://attack.mitre.org/software/S1042) variant has used HTTP for C2.(Citation: Mandiant UNC3890 Aug 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d3d7c2a6-33ae-460d-a759-e3f755264d0e`.
