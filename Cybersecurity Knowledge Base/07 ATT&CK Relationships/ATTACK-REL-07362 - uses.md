---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1041"
target_object: "T1036.005"
stix_relationship_id: "relationship--e3caf4ea-efa0-4919-8bef-1b56425f7ef5"
---
# Relationship 7362: S1041 — uses → T1036.005

**Source object:** [[01 ATT&CK/S1041 - Chinoxy|S1041: Chinoxy]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Chinoxy](https://attack.mitre.org/software/S1041) has used the name `eoffice.exe` in attempt to appear as a legitimate file.(Citation: Bitdefender FunnyDream Campaign November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e3caf4ea-efa0-4919-8bef-1b56425f7ef5`.
