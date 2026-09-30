---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0483"
target_object: "T1055.012"
stix_relationship_id: "relationship--1094b816-3db3-40a6-9b86-6a4323d4818f"
---
# Relationship 7463: S0483 — uses → T1055.012

**Source object:** [[01 ATT&CK/S0483 - IcedID|S0483: IcedID]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.012 - Process Hollowing|T1055.012: Process Hollowing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[IcedID](https://attack.mitre.org/software/S0483) can inject a [Cobalt Strike](https://attack.mitre.org/software/S0154) beacon into cmd.exe via process hallowing.(Citation: DFIR_Quantum_Ransomware)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1094b816-3db3-40a6-9b86-6a4323d4818f`.
