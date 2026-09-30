---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0100"
target_object: "T1059.001"
stix_relationship_id: "relationship--5b2457a6-a2b8-4809-a2a0-68d1c74bbb9b"
---
# Relationship 7232: G0100 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0100 - Inception|G0100: Inception]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Inception](https://attack.mitre.org/groups/G0100) has used PowerShell to execute malicious commands and payloads.(Citation: Unit 42 Inception November 2018)(Citation: Kaspersky Cloud Atlas December 2014)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5b2457a6-a2b8-4809-a2a0-68d1c74bbb9b`.
