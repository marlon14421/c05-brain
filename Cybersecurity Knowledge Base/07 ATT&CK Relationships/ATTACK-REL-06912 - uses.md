---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0273"
target_object: "T1059.001"
stix_relationship_id: "relationship--749b0a26-fbf8-4858-a545-5faca77adead"
---
# Relationship 6912: S0273 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0273 - Socksbot|S0273: Socksbot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Socksbot](https://attack.mitre.org/software/S0273) can write and execute PowerShell scripts.(Citation: TrendMicro Patchwork Dec 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--749b0a26-fbf8-4858-a545-5faca77adead`.
