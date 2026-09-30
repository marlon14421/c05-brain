---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0268"
target_object: "T1059.003"
stix_relationship_id: "relationship--ca3f0924-306a-409e-a1b6-135b781f3dbf"
---
# Relationship 5311: S0268 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0268 - Bisonal|S0268: Bisonal]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bisonal](https://attack.mitre.org/software/S0268) has launched cmd.exe and used the ShellExecuteW() API function to execute commands on the system.(Citation: Unit 42 Bisonal July 2018)(Citation: Kaspersky CactusPete Aug 2020)(Citation: Talos Bisonal Mar 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ca3f0924-306a-409e-a1b6-135b781f3dbf`.
