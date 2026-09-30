---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0668"
target_object: "T1059.003"
stix_relationship_id: "relationship--5c2fe9e9-cb7e-418a-84f1-9966854b4c27"
---
# Relationship 5123: S0668 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0668 - TinyTurla|S0668: TinyTurla]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[TinyTurla](https://attack.mitre.org/software/S0668) has been installed using a .bat file.(Citation: Talos TinyTurla September 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5c2fe9e9-cb7e-418a-84f1-9966854b4c27`.
