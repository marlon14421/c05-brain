---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0340"
target_object: "T1105"
stix_relationship_id: "relationship--c77d6f2a-664e-4bbb-bf86-c2c58adbdc84"
---
# Relationship 5691: S0340 — uses → T1105

**Source object:** [[01 ATT&CK/S0340 - Octopus|S0340: Octopus]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1105 - Ingress Tool Transfer|T1105: Ingress Tool Transfer]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Octopus](https://attack.mitre.org/software/S0340) can download additional files and tools onto the victim’s machine.(Citation: Securelist Octopus Oct 2018)(Citation: Security Affairs DustSquad Oct 2018)(Citation: ESET Nomadic Octopus 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c77d6f2a-664e-4bbb-bf86-c2c58adbdc84`.
