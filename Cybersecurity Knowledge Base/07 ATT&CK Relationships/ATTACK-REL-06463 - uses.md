---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0451"
target_object: "T1059.003"
stix_relationship_id: "relationship--e42b5898-2a13-4266-941c-8ef8b8090c8d"
---
# Relationship 6463: S0451 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0451 - LoudMiner|S0451: LoudMiner]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[LoudMiner](https://attack.mitre.org/software/S0451) used a batch script to run the Linux virtual machine as a service.(Citation: ESET LoudMiner June 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e42b5898-2a13-4266-941c-8ef8b8090c8d`.
