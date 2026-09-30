---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1078"
target_object: "T1106"
stix_relationship_id: "relationship--3fa24e29-2791-4b10-8014-bfa817c3a2f2"
---
# Relationship 8631: S1078 — uses → T1106

**Source object:** [[01 ATT&CK/S1078 - RotaJakiro|S1078: RotaJakiro]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

When executing with non-root permissions, [RotaJakiro](https://attack.mitre.org/software/S1078) uses the the `shmget` API to create shared memory between other known [RotaJakiro](https://attack.mitre.org/software/S1078) processes. [RotaJakiro](https://attack.mitre.org/software/S1078) also uses the `execvp` API to help its dead process "resurrect".(Citation: RotaJakiro 2021 netlab360 analysis)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3fa24e29-2791-4b10-8014-bfa817c3a2f2`.
