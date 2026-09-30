---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1146"
target_object: "T1018"
stix_relationship_id: "relationship--a3742518-c231-4492-9673-95e095badddf"
---
# Relationship 7409: S1146 — uses → T1018

**Source object:** [[01 ATT&CK/S1146 - MgBot|S1146: MgBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[MgBot](https://attack.mitre.org/software/S1146) includes modules for performing ARP scans of local connected systems.(Citation: Symantec Daggerfly 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a3742518-c231-4492-9673-95e095badddf`.
