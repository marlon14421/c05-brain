---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0623"
target_object: "T1190"
stix_relationship_id: "relationship--26ecce49-13ab-43a9-a626-10dae30b6961"
---
# Relationship 5851: S0623 — uses → T1190

**Source object:** [[01 ATT&CK/S0623 - Siloscape|S0623: Siloscape]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1190 - Exploit Public-Facing Application|T1190: Exploit Public-Facing Application]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Siloscape](https://attack.mitre.org/software/S0623) is executed after the attacker gains initial access to a Windows container using a known vulnerability.(Citation: Unit 42 Siloscape Jun 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--26ecce49-13ab-43a9-a626-10dae30b6961`.
