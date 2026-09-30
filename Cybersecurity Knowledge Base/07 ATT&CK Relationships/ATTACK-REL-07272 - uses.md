---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0018"
target_object: "T1059.003"
stix_relationship_id: "relationship--fb6f077c-06a2-46bb-9aef-959ef818d4aa"
---
# Relationship 7272: G0018 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0018 - admin@338|G0018: admin@338]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Following exploitation with [LOWBALL](https://attack.mitre.org/software/S0042) malware, [admin@338](https://attack.mitre.org/groups/G0018) actors created a file containing a list of commands to be executed on the compromised computer.(Citation: FireEye admin@338)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--fb6f077c-06a2-46bb-9aef-959ef818d4aa`.
