---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0162"
target_object: "T1071.001"
stix_relationship_id: "relationship--cdca2bdf-a29b-45d5-90ff-17ab56b094a4"
---
# Relationship 8645: S0162 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0162 - Komplex|S0162: Komplex]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Komplex](https://attack.mitre.org/software/S0162) C2 channel uses HTTP POST requests.(Citation: Sofacy Komplex Trojan)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--cdca2bdf-a29b-45d5-90ff-17ab56b094a4`.
