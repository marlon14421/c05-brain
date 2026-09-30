---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1136"
target_object: "T1561.002"
stix_relationship_id: "relationship--7145e20d-4c16-47bf-bf13-40b4e031d0e5"
---
# Relationship 5333: S1136 — uses → T1561.002

**Source object:** [[01 ATT&CK/S1136 - BFG Agonizer|S1136: BFG Agonizer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1561.002 - Disk Structure Wipe|T1561.002: Disk Structure Wipe]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BFG Agonizer](https://attack.mitre.org/software/S1136) retrieves a device handle to \\\\.\\PhysicalDrive0 to wipe the boot sector of a given disk.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7145e20d-4c16-47bf-bf13-40b4e031d0e5`.
