---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9001"
target_object: "T1480"
stix_relationship_id: "relationship--69e823be-ab39-44c1-b56f-b371a2a0118b"
---
# Relationship 7191: S9001 — uses → T1480

**Source object:** [[01 ATT&CK/S9001 - SystemBC|S9001: SystemBC]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1480 - Execution Guardrails|T1480: Execution Guardrails]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[SystemBC](https://attack.mitre.org/software/S9001) has checked if the last characters of DNS server names end in .bit before initializing C2 communication.(Citation: HarmonProofpoint_SystemBC_Aug2019) [SystemBC](https://attack.mitre.org/software/S9001) has identified running processes associated with anti-virus solutions to include `a2guard.exe` to determine whether it executes or not.(Citation: SophosGnGal_SystemBC_Dec2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--69e823be-ab39-44c1-b56f-b371a2a0118b`.
