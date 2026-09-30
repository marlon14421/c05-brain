---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1059.001"
stix_relationship_id: "relationship--98e2f79a-e394-4d26-a82e-a15c235d28dd"
---
# Relationship 9943: G1051 — uses → T1059.001

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has leveraged PowerShell for execution and defense evasion.(Citation: Check Point Medusa Ransomware April 2025)(Citation: CISA Medusa Group Medusa Ransomware March 2025)(Citation: Intel471 Medusa Ransomware May 2025) [Medusa Group](https://attack.mitre.org/groups/G1051) has also utilized PowerShell to execute a bitsadmin transfer from file hosting site.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--98e2f79a-e394-4d26-a82e-a15c235d28dd`.
