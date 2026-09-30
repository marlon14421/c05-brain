---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1240"
target_object: "T1539"
stix_relationship_id: "relationship--98847982-f5fe-4c8e-bd90-b24ba3ff58bd"
---
# Relationship 5840: S1240 — uses → T1539

**Source object:** [[01 ATT&CK/S1240 - RedLine Stealer|S1240: RedLine Stealer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1539 - Steal Web Session Cookie|T1539: Steal Web Session Cookie]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[RedLine Stealer](https://attack.mitre.org/software/S1240) has stolen browser cookies and settings.(Citation: ESET RedLine Stealer November 2024)(Citation: Kroll RedLine Stealer August 2024)(Citation: Proofpoint RedLine Stealer March 2020)(Citation: Splunk RedLine Stealer June 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98847982-f5fe-4c8e-bd90-b24ba3ff58bd`.
