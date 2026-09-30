---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0032"
target_object: "T1082"
stix_relationship_id: "relationship--aee29ae1-4544-4fc8-b30b-4717888991ca"
---
# Relationship 5735: S0032 — uses → T1082

**Source object:** [[01 ATT&CK/S0032 - gh0st RAT|S0032: gh0st RAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[gh0st RAT](https://attack.mitre.org/software/S0032) has gathered system architecture, processor, OS configuration, and installed hardware information.(Citation: Gh0stRAT ATT March 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aee29ae1-4544-4fc8-b30b-4717888991ca`.
