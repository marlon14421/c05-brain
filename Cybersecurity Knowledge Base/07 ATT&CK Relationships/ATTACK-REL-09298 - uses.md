---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0251"
target_object: "T1057"
stix_relationship_id: "relationship--1051f320-91fa-4f89-8abe-a851a56e18a7"
---
# Relationship 9298: S0251 — uses → T1057

**Source object:** [[01 ATT&CK/S0251 - Zebrocy|S0251: Zebrocy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1057 - Process Discovery|T1057: Process Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Zebrocy](https://attack.mitre.org/software/S0251) uses the tasklist and wmic process get Capture, ExecutablePath commands to gather the processes running on the system.(Citation: Unit42 Cannon Nov 2018)(Citation: ESET Zebrocy Nov 2018)(Citation: Unit42 Sofacy Dec 2018)(Citation: ESET Zebrocy May 2019)(Citation: Accenture SNAKEMACKEREL Nov 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1051f320-91fa-4f89-8abe-a851a56e18a7`.
