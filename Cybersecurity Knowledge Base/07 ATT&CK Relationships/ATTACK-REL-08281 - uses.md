---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0017"
target_object: "T1057"
stix_relationship_id: "relationship--93fe5493-d3c1-4db2-8228-61da951c660e"
---
# Relationship 8281: S0017 — uses → T1057

**Source object:** [[01 ATT&CK/S0017 - BISCUIT|S0017: BISCUIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BISCUIT](https://attack.mitre.org/software/S0017) has a command to enumerate running processes and identify their owners.(Citation: Mandiant APT1 Appendix)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93fe5493-d3c1-4db2-8228-61da951c660e`.
