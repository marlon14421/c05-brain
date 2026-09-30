---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0045"
target_object: "T1047"
stix_relationship_id: "relationship--04203d88-5fe1-4e63-be65-51a17705716b"
---
# Relationship 7455: G0045 — uses → T1047

**Source object:** [[01 ATT&CK/G0045 - menuPass|G0045: menuPass]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1047 - Windows Management Instrumentation|T1047: Windows Management Instrumentation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[menuPass](https://attack.mitre.org/groups/G0045) has used a modified version of pentesting script wmiexec.vbs, which logs into a remote machine using WMI.(Citation: PWC Cloud Hopper Technical Annex April 2017)(Citation: Github AD-Pentest-Script)(Citation: Symantec Cicada November 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--04203d88-5fe1-4e63-be65-51a17705716b`.
