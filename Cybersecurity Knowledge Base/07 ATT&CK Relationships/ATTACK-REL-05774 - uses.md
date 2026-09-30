---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0660"
target_object: "T1564.001"
stix_relationship_id: "relationship--11180322-a9e0-4f20-94e1-d47f95db06f8"
---
# Relationship 5774: S0660 — uses → T1564.001

**Source object:** [[01 ATT&CK/S0660 - Clambling|S0660: Clambling]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1564.001 - Hidden Files and Directories|T1564.001: Hidden Files and Directories]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Clambling](https://attack.mitre.org/software/S0660) has the ability to set its file attributes to hidden.(Citation: Trend Micro DRBControl February 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--11180322-a9e0-4f20-94e1-d47f95db06f8`.
