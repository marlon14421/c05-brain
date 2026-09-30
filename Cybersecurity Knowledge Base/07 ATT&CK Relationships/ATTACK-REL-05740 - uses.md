---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1547.001"
stix_relationship_id: "relationship--4739d942-9d7f-4d7b-8aaf-af5464f76d44"
---
# Relationship 5740: S1111 — uses → T1547.001

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1547.001 - Registry Run Keys - Startup Folder|T1547.001: Registry Run Keys / Startup Folder]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) installation includes AutoIt script execution creating a shortcut to itself as an LNK object, such as bill.lnk, in the victim startup folder.(Citation: Ensilo Darkgate 2018)(Citation: Rapid7 BlackBasta 2024) [DarkGate](https://attack.mitre.org/software/S1111) installation finishes with the creation of a registry Run key.(Citation: Ensilo Darkgate 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4739d942-9d7f-4d7b-8aaf-af5464f76d44`.
