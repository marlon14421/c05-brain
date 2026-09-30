---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0491"
target_object: "T1560.003"
stix_relationship_id: "relationship--3ad041f8-30ca-44bb-bad5-2e5b3e5d6242"
---
# Relationship 5935: S0491 — uses → T1560.003

**Source object:** [[01 ATT&CK/S0491 - StrongPity|S0491: StrongPity]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1560.003 - Archive via Custom Method|T1560.003: Archive via Custom Method]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[StrongPity](https://attack.mitre.org/software/S0491) can compress and encrypt archived files into multiple .sft files with a repeated xor encryption scheme.(Citation: Talos Promethium June 2020)(Citation: Bitdefender StrongPity June 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ad041f8-30ca-44bb-bad5-2e5b3e5d6242`.
