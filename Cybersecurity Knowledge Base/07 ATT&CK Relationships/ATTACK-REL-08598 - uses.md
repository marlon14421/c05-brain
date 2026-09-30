---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0670"
target_object: "T1082"
stix_relationship_id: "relationship--384b6787-f69b-4d81-bc5e-c01a5c5b026e"
---
# Relationship 8598: S0670 — uses → T1082

**Source object:** [[01 ATT&CK/S0670 - WarzoneRAT|S0670: WarzoneRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1082 - System Information Discovery|T1082: System Information Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WarzoneRAT](https://attack.mitre.org/software/S0670) can collect compromised host information, including OS version, PC name, RAM size, and CPU details.(Citation: Check Point Warzone Feb 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--384b6787-f69b-4d81-bc5e-c01a5c5b026e`.
