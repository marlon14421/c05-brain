---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9019"
target_object: "T1673"
stix_relationship_id: "relationship--1bfece9c-8ba6-499d-a25e-fab239e63f0d"
---
# Relationship 9896: S9019 — uses → T1673

**Source object:** [[01 ATT&CK/S9019 - PureCrypter|S9019: PureCrypter]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1673 - Virtual Machine Discovery|T1673: Virtual Machine Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[PureCrypter](https://attack.mitre.org/software/S9019) can identify virtual machines by querying the WMI object Win32_ComputerSystem for manufacturer and model and check it against the regular expression Microsoft|VMWare|Virtual.(Citation: Zscaler PureCrypter JUN 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1bfece9c-8ba6-499d-a25e-fab239e63f0d`.
