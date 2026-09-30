---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1201"
target_object: "T1112"
stix_relationship_id: "relationship--4a2d2699-a2c0-40e4-8e8d-3450155b9923"
---
# Relationship 6046: S1201 — uses → T1112

**Source object:** [[01 ATT&CK/S1201 - TRANSLATEXT|S1201: TRANSLATEXT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1112 - Modify Registry|T1112: Modify Registry]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TRANSLATEXT](https://attack.mitre.org/software/S1201) has modified the following registry key to install itself as the value, granting permission to install specified extensions: ` HKCU\Software\Policies\Google\Chrome\ExtensionInstallForcelist`.(Citation: Zscaler Kimsuky TRANSLATEXT)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4a2d2699-a2c0-40e4-8e8d-3450155b9923`.
