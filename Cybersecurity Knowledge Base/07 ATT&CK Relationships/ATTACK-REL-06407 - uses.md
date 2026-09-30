---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1217"
target_object: "T1673"
stix_relationship_id: "relationship--8b6d278e-5a90-4656-9546-87ce143007d7"
---
# Relationship 6407: S1217 — uses → T1673

**Source object:** [[01 ATT&CK/S1217 - VIRTUALPITA|S1217: VIRTUALPITA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1673 - Virtual Machine Discovery|T1673: Virtual Machine Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[VIRTUALPITA](https://attack.mitre.org/software/S1217) can target specific guest virtual machines for script execution.(Citation: Google Cloud Threat Intelligence ESXi VIBs 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8b6d278e-5a90-4656-9546-87ce143007d7`.
