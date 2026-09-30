---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0559"
target_object: "T1027.005"
stix_relationship_id: "relationship--e88a2959-311f-40c9-adc9-895f38bb1dd7"
---
# Relationship 5789: S0559 — uses → T1027.005

**Source object:** [[01 ATT&CK/S0559 - SUNBURST|S0559: SUNBURST]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.005 - Indicator Removal from Tools|T1027.005: Indicator Removal from Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SUNBURST](https://attack.mitre.org/software/S0559) source code used generic variable names and pre-obfuscated strings, and was likely sanitized of developer comments before being added to [SUNSPOT](https://attack.mitre.org/software/S0562).(Citation: CrowdStrike SUNSPOT Implant January 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e88a2959-311f-40c9-adc9-895f38bb1dd7`.
