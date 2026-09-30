---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0102"
target_object: "T1003.001"
stix_relationship_id: "relationship--bfd2f3f1-3a5f-4500-be4e-39e3f8d6cb8e"
---
# Relationship 7807: G0102 — uses → T1003.001

**Source object:** [[01 ATT&CK/G0102 - Wizard Spider|G0102: Wizard Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Wizard Spider](https://attack.mitre.org/groups/G0102) has dumped the lsass.exe memory to harvest credentials with the use of open-source tool [LaZagne](https://attack.mitre.org/software/S0349).(Citation: Mandiant FIN12 Oct 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bfd2f3f1-3a5f-4500-be4e-39e3f8d6cb8e`.
