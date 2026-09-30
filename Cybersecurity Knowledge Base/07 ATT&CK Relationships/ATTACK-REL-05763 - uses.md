---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1003.003"
stix_relationship_id: "relationship--a1e10048-626c-4e64-9bdb-fd576be8c19f"
---
# Relationship 5763: G0102 — uses → T1003.003

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.003 - NTDS|T1003.003: NTDS]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has gained access to credentials via exported copies of the ntds.dit Active Directory database. [Wizard Spider](https://attack.mitre.org/groups/G0102) has also created a volume shadow copy and used a batch script file to collect NTDS.dit with the use of the Windows utility, ntdsutil.(Citation: FireEye KEGTAP SINGLEMALT October 2020)(Citation: Mandiant FIN12 Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a1e10048-626c-4e64-9bdb-fd576be8c19f`.
