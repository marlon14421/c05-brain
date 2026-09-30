---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0046"
target_object: "T1059.005"
stix_relationship_id: "relationship--3f0e6cfa-7edc-4eaa-bc03-754d0f46d605"
---
# Relationship 6386: G0046 — uses → T1059.005

**Source object:** [[01 ATT&CK/G0046 - FIN7|G0046: FIN7]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.005 - Visual Basic|T1059.005: Visual Basic]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[FIN7](https://attack.mitre.org/groups/G0046) used VBS scripts to help perform tasks on the victim's machine.(Citation: FireEye FIN7 Aug 2018)(Citation: Flashpoint FIN 7 March 2019)(Citation: CrowdStrike Carbon Spider August 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3f0e6cfa-7edc-4eaa-bc03-754d0f46d605`.
