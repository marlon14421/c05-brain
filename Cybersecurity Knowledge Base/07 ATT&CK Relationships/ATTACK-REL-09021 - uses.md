---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0682"
target_object: "T1071.001"
stix_relationship_id: "relationship--9199705b-d90f-4f46-908a-e419501c8712"
---
# Relationship 9021: S0682 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0682 - TrailBlazer|S0682: TrailBlazer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TrailBlazer](https://attack.mitre.org/software/S0682) has used HTTP requests for C2.(Citation: CrowdStrike StellarParticle January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9199705b-d90f-4f46-908a-e419501c8712`.
