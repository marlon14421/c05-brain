---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1212"
target_object: "T1057"
stix_relationship_id: "relationship--a8ef854e-4c3a-4adc-9022-d8d12adc00bb"
---
# Relationship 8903: S1212 — uses → T1057

**Source object:** [[01 ATT&CK/S1212 - RansomHub|S1212: RansomHub]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RansomHub](https://attack.mitre.org/software/S1212) can stop processes associated with files currently in use to maximize the impact of encryption.(Citation: CISA RansomHub AUG 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a8ef854e-4c3a-4adc-9022-d8d12adc00bb`.
