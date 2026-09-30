---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0431"
target_object: "T1518"
stix_relationship_id: "relationship--d07460c8-0d13-4c25-81f7-56e5198f07c5"
---
# Relationship 5374: S0431 — uses → T1518

**Source object:** [[01 ATT&CK/S0431 - HotCroissant|S0431: HotCroissant]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1518 - Software Discovery|T1518: Software Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[HotCroissant](https://attack.mitre.org/software/S0431) can retrieve a list of applications from the SOFTWARE\Microsoft\Windows\CurrentVersion\App Paths registry key.(Citation: Carbon Black HotCroissant April 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d07460c8-0d13-4c25-81f7-56e5198f07c5`.
