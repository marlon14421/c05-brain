---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0168"
target_object: "T1055.003"
stix_relationship_id: "relationship--86ebda8c-df0c-4d76-970b-27bf392606a7"
---
# Relationship 6439: S0168 — uses → T1055.003

**Source object:** [[01 ATT&CK/S0168 - Gazer|S0168: Gazer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055.003 - Thread Execution Hijacking|T1055.003: Thread Execution Hijacking]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gazer](https://attack.mitre.org/software/S0168) performs thread execution hijacking to inject its orchestrator into a running thread from a remote process.(Citation: ESET Gazer Aug 2017)(Citation: Securelist WhiteBear Aug 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--86ebda8c-df0c-4d76-970b-27bf392606a7`.
