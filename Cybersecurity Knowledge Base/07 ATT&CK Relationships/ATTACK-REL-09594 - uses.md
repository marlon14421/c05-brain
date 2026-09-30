---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0033"
target_object: "T1059.001"
stix_relationship_id: "relationship--e2ce90d2-7470-4f2d-a86c-f429b934ab35"
---
# Relationship 9594: G0033 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0033 - Poseidon Group|G0033: Poseidon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

The [Poseidon Group](https://attack.mitre.org/groups/G0033)'s Information Gathering Tool (IGT) includes PowerShell components.(Citation: Kaspersky Poseidon Group)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e2ce90d2-7470-4f2d-a86c-f429b934ab35`.
