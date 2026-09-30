---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0176"
target_object: "T1569.002"
stix_relationship_id: "relationship--91ca1017-0b33-4fa1-a61f-b3dae24c7e40"
---
# Relationship 8029: S0176 — uses → T1569.002

**Source object:** [[01 ATT&CK/S0176 - Wingbird|S0176: Wingbird]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1569.002 - Service Execution|T1569.002: Service Execution]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wingbird](https://attack.mitre.org/software/S0176) uses services.exe to register a new autostart service named "Audit Service" using a copy of the local lsass.exe file.(Citation: Microsoft SIR Vol 21)(Citation: Microsoft Wingbird Nov 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--91ca1017-0b33-4fa1-a61f-b3dae24c7e40`.
