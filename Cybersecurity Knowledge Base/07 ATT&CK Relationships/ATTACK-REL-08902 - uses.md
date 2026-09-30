---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0061"
target_object: "T1685"
stix_relationship_id: "relationship--ec31ed0a-920e-469f-a7b3-5adcb0db8f61"
---
# Relationship 8902: S0061 — uses → T1685

**Source object:** [[01 ATT&CK/S0061 - HDoor|S0061: HDoor]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HDoor](https://attack.mitre.org/software/S0061) kills anti-virus found on the victim.(Citation: Baumgartner Naikon 2015)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec31ed0a-920e-469f-a7b3-5adcb0db8f61`.
