---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1059.003"
stix_relationship_id: "relationship--dea36846-b8ad-4926-a242-9fa2d12069c8"
---
# Relationship 9667: G0045 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) executes commands using a command-line interface and reverse shell. The group has used a modified version of pentesting script wmiexec.vbs to execute commands.(Citation: PWC Cloud Hopper April 2017)(Citation: PWC Cloud Hopper Technical Annex April 2017)(Citation: Github AD-Pentest-Script)(Citation: FireEye APT10 Sept 2018) [menuPass](https://attack.mitre.org/groups/G0045) has used malicious macros embedded inside Office documents to execute files.(Citation: Accenture Hogfish April 2018)(Citation: FireEye APT10 Sept 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dea36846-b8ad-4926-a242-9fa2d12069c8`.
