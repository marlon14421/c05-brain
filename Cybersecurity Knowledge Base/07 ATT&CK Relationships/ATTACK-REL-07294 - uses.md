---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0032"
target_object: "T1070"
stix_relationship_id: "relationship--bcee230a-c671-4c71-afbf-d6216aeee5b6"
---
# Relationship 7294: G0032 — uses → T1070

**Source object:** [[01 ATT&CK/G0032 - Lazarus Group|G0032: Lazarus Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1070 - Indicator Removal|T1070: Indicator Removal]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Lazarus Group](https://attack.mitre.org/groups/G0032) has restored malicious [KernelCallbackTable](https://attack.mitre.org/techniques/T1574/013) code to its original state after the process execution flow has been hijacked.(Citation: Lazarus APT January 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--bcee230a-c671-4c71-afbf-d6216aeee5b6`.
