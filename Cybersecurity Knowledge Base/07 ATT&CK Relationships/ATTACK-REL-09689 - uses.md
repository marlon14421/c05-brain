---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0696"
target_object: "T1547.001"
stix_relationship_id: "relationship--83561fd5-18cf-47df-a412-45614f3142bd"
---
# Relationship 9689: S0696 — uses → T1547.001

**Source object:** [[01 ATT&CK/S0696 - Flagpro|S0696: Flagpro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Flagpro](https://attack.mitre.org/software/S0696) has dropped an executable file to the startup directory.(Citation: NTT Security Flagpro new December 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--83561fd5-18cf-47df-a412-45614f3142bd`.
