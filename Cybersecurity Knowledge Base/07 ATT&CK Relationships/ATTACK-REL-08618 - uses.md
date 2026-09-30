---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0089"
target_object: "T1070"
stix_relationship_id: "relationship--12c761e7-f026-4e14-80fb-da9f4cb0ca38"
---
# Relationship 8618: S0089 — uses → T1070

**Source object:** [[01 ATT&CK/S0089 - BlackEnergy|S0089: BlackEnergy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BlackEnergy](https://attack.mitre.org/software/S0089) has removed the watermark associated with enabling the TESTSIGNING boot configuration option by removing the relevant strings in the user32.dll.mui of the system.(Citation: F-Secure BlackEnergy 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--12c761e7-f026-4e14-80fb-da9f4cb0ca38`.
