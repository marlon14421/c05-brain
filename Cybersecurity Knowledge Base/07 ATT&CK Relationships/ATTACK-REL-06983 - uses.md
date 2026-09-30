---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1490"
stix_relationship_id: "relationship--773fc200-e44d-4049-b972-043c1e3d9035"
---
# Relationship 6983: G0102 — uses → T1490

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1490 - Inhibit System Recovery|T1490: Inhibit System Recovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has used WMIC and vssadmin to manually delete volume shadow copies. [Wizard Spider](https://attack.mitre.org/groups/G0102) has also used [Conti](https://attack.mitre.org/software/S0575) ransomware to delete volume shadow copies automatically with the use of vssadmin.(Citation: Mandiant FIN12 Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--773fc200-e44d-4049-b972-043c1e3d9035`.
