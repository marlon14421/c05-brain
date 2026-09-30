---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0687"
target_object: "T1036.005"
stix_relationship_id: "relationship--1ad60707-d84f-4768-9013-6b499de49c40"
---
# Relationship 9414: S0687 — uses → T1036.005

**Source object:** [[01 ATT&CK/S0687 - Cyclops Blink|S0687: Cyclops Blink]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036.005 - Match Legitimate Resource Name or Location|T1036.005: Match Legitimate Resource Name or Location]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Cyclops Blink](https://attack.mitre.org/software/S0687) can rename its running process to [kworker:0/1] to masquerade as a Linux kernel thread. [Cyclops Blink](https://attack.mitre.org/software/S0687) has also named RC scripts used for persistence after WatchGuard artifacts.(Citation: NCSC Cyclops Blink February 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1ad60707-d84f-4768-9013-6b499de49c40`.
