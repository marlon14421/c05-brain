---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0332"
target_object: "T1059.003"
stix_relationship_id: "relationship--8f58f0fa-54ca-412e-a681-2f864e217039"
---
# Relationship 6655: S0332 — uses → T1059.003

**Source object:** [[01 ATT&CK/S0332 - Remcos|S0332: Remcos]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.003 - Windows Command Shell|T1059.003: Windows Command Shell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Remcos](https://attack.mitre.org/software/S0332) can launch a remote command line to execute commands on the victim’s machine.(Citation: Fortinet Remcos Feb 2017)(Citation: Fortinet Remcos Campaign NOV 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8f58f0fa-54ca-412e-a681-2f864e217039`.
