---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0685"
target_object: "T1059.001"
stix_relationship_id: "relationship--5238d74f-8d6c-420f-a521-f68937934842"
---
# Relationship 6949: S0685 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0685 - PowerPunch|S0685: PowerPunch]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PowerPunch](https://attack.mitre.org/software/S0685) has the ability to execute through PowerShell.(Citation: Microsoft Actinium February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5238d74f-8d6c-420f-a521-f68937934842`.
