---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0377"
target_object: "T1685"
stix_relationship_id: "relationship--be278ea8-19b6-4d42-ac7f-9ee8681a17e3"
---
# Relationship 8069: S0377 — uses → T1685

**Source object:** [[01 ATT&CK/S0377 - Ebury|S0377: Ebury]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1685 - Disable or Modify Tools|T1685: Disable or Modify Tools]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Ebury](https://attack.mitre.org/software/S0377) can disable SELinux Role-Based Access Control and deactivate PAM modules.(Citation: ESET Ebury Oct 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--be278ea8-19b6-4d42-ac7f-9ee8681a17e3`.
