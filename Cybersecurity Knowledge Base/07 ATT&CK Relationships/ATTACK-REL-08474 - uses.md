---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0078"
target_object: "T1059.001"
stix_relationship_id: "relationship--3ed930d6-ab79-4642-8320-2ed59d899b6d"
---
# Relationship 8474: G0078 — uses → T1059.001

**Source object:** [[01 ATT&CK/G0078 - Gorgon Group|G0078: Gorgon Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1059.001 - PowerShell|T1059.001: PowerShell]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Gorgon Group](https://attack.mitre.org/groups/G0078) malware can use PowerShell commands to download and execute a payload and open a decoy document on the victim’s machine.(Citation: Unit 42 Gorgon Group Aug 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3ed930d6-ab79-4642-8320-2ed59d899b6d`.
