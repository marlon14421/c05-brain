---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0534"
target_object: "T1059.001"
stix_relationship_id: "relationship--2cd5235f-1f0b-4f58-a931-d3b940b62cbf"
---
# Relationship 7279: S0534 — uses → T1059.001

**Source object:** [[01 ATT&CK/S0534 - Bazar|S0534: Bazar]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Bazar](https://attack.mitre.org/software/S0534) can execute a PowerShell script received from C2.(Citation: NCC Group Team9 June 2020)(Citation: CrowdStrike Wizard Spider October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2cd5235f-1f0b-4f58-a931-d3b940b62cbf`.
