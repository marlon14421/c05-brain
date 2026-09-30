---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0007"
target_object: "T1059.003"
stix_relationship_id: "relationship--5799308b-e710-40b8-ad64-2b7916673560"
---
# Relationship 5321: G0007 — uses → T1059.003

**Source object:** [[01 ATT&CK/G0007 - APT28|G0007: APT28]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

An [APT28](https://attack.mitre.org/groups/G0007) loader Trojan uses a cmd.exe and batch script to run its payload.(Citation: Unit 42 Playbook Dec 2017) The group has also used macros to execute payloads.(Citation: Talos Seduploader Oct 2017)(Citation: Unit42 Cannon Nov 2018)(Citation: Accenture SNAKEMACKEREL Nov 2018)(Citation: TrendMicro Pawn Storm Dec 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5799308b-e710-40b8-ad64-2b7916673560`.
