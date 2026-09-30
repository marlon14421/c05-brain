---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0417"
target_object: "T1124"
stix_relationship_id: "relationship--3ce0fee3-3ad5-49b9-8213-871484674d93"
---
# Relationship 6959: S0417 — uses → T1124

**Source object:** [[01 ATT&CK/S0417 - GRIFFON|S0417: GRIFFON]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[GRIFFON](https://attack.mitre.org/software/S0417) has used a reconnaissance module that can be used to retrieve the date and time of the system.(Citation: SecureList Griffon May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ce0fee3-3ad5-49b9-8213-871484674d93`.
