---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0234"
target_object: "T1106"
stix_relationship_id: "relationship--bd5fd2c2-a9a3-401e-8723-92df94f9c482"
---
# Relationship 7507: S0234 — uses → T1106

**Source object:** [[01 ATT&CK/S0234 - Bandook|S0234: Bandook]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bandook](https://attack.mitre.org/software/S0234) has used the ShellExecuteW() function call.(Citation: CheckPoint Bandook Nov 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bd5fd2c2-a9a3-401e-8723-92df94f9c482`.
