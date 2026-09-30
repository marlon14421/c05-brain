---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1150"
target_object: "T1480"
stix_relationship_id: "relationship--c29450bf-20a4-47f8-8ef9-7c6559cfad75"
---
# Relationship 6839: S1150 — uses → T1480

**Source object:** [[01 ATT&CK/S1150 - ROADSWEEP|S1150: ROADSWEEP]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ROADSWEEP](https://attack.mitre.org/software/S1150) requires four command line arguments to execute correctly, otherwise it will produce a message box and halt execution.(Citation: Mandiant ROADSWEEP August 2022)(Citation: CISA Iran Albanian Attacks September 2022)(Citation: Microsoft Albanian Government Attacks September 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c29450bf-20a4-47f8-8ef9-7c6559cfad75`.
