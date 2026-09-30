---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1022"
target_object: "T1059.003"
stix_relationship_id: "relationship--a247d3fe-a150-4096-a6e1-1d150e3e407d"
---
# Relationship 6508: G1022 — uses → T1059.003

**Source object:** [[01 ATT&CK/G1022 - ToddyCat|G1022: ToddyCat]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ToddyCat](https://attack.mitre.org/groups/G1022) has used .bat scripts and `cmd` for execution on compromised hosts.(Citation: Kaspersky ToddyCat Check Logs October 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--a247d3fe-a150-4096-a6e1-1d150e3e407d`.
