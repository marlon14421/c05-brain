---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1003.001"
stix_relationship_id: "relationship--e71903c4-a7af-4317-adf0-10f76d3d4e15"
---
# Relationship 8303: G0007 — uses → T1003.001

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1003.001 - LSASS Memory|T1003.001: LSASS Memory]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[APT28](https://attack.mitre.org/groups/G0007) regularly deploys both publicly available (ex: [Mimikatz](https://attack.mitre.org/software/S0002)) and custom password retrieval tools on victims.(Citation: ESET Sednit Part 2)(Citation: DOJ GRU Indictment Jul 2018) They have also dumped the LSASS process memory using the MiniDump function.(Citation: Cybersecurity Advisory GRU Brute Force Campaign July 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e71903c4-a7af-4317-adf0-10f76d3d4e15`.
