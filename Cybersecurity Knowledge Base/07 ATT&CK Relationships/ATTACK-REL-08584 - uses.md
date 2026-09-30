---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1136"
target_object: "T1554"
stix_relationship_id: "relationship--4cc2992e-016b-47cb-a1be-5bcf808a34c2"
---
# Relationship 8584: S1136 — uses → T1554

**Source object:** [[01 ATT&CK/S1136 - BFG Agonizer|S1136: BFG Agonizer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1554 - Compromise Host Software Binary|T1554: Compromise Host Software Binary]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[BFG Agonizer](https://attack.mitre.org/software/S1136) uses DLL unhooking to remove user mode inline hooks that security solutions often implement. [BFG Agonizer](https://attack.mitre.org/software/S1136) also uses IAT unhooking to remove user-mode IAT hooks that security solutions also use.(Citation: Unit42 Agrius 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4cc2992e-016b-47cb-a1be-5bcf808a34c2`.
