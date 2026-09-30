---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1018"
stix_relationship_id: "relationship--03f32a8b-4cd9-488c-9759-37f3dff9faea"
---
# Relationship 5254: G0045 — uses → T1018

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1018 - Remote System Discovery|T1018: Remote System Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) uses scripts to enumerate IP ranges on the victim network. [menuPass](https://attack.mitre.org/groups/G0045) has also issued the command net view /domain to a [PlugX](https://attack.mitre.org/software/S0013) implant to gather information about remote systems on the network.(Citation: PWC Cloud Hopper Technical Annex April 2017)(Citation: FireEye APT10 April 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--03f32a8b-4cd9-488c-9759-37f3dff9faea`.
