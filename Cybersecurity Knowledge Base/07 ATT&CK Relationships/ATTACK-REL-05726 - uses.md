---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0249"
target_object: "T1082"
stix_relationship_id: "relationship--c1544dec-4586-466a-b730-862c06e9e3c7"
---
# Relationship 5726: S0249 — uses → T1082

**Source object:** [[01 ATT&CK/S0249 - Gold Dragon|S0249: Gold Dragon]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gold Dragon](https://attack.mitre.org/software/S0249) collects endpoint information using the systeminfo command.(Citation: McAfee Gold Dragon)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c1544dec-4586-466a-b730-862c06e9e3c7`.
