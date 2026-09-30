---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0603"
target_object: "T1071.001"
stix_relationship_id: "relationship--81763def-b0ec-4938-832d-cffb382bb4a8"
---
# Relationship 5470: S0603 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0603 - Stuxnet|S0603: Stuxnet]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Stuxnet](https://attack.mitre.org/software/S0603) uses HTTP to communicate with a command and control server. (Citation: Nicolas Falliere, Liam O Murchu, Eric Chien February 2011)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--81763def-b0ec-4938-832d-cffb382bb4a8`.
