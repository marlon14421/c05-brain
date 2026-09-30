---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0284"
target_object: "T1553.002"
stix_relationship_id: "relationship--c9e900cd-4c6b-4027-b6ca-b93b55c3c5e7"
---
# Relationship 5821: S0284 — uses → T1553.002

**Source object:** [[01 ATT&CK/S0284 - More_eggs|S0284: More_eggs]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1553.002 - Code Signing|T1553.002: Code Signing]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[More_eggs](https://attack.mitre.org/software/S0284) has used a signed binary shellcode loader and a signed Dynamic Link Library (DLL) to create a reverse shell.(Citation: Security Intelligence More Eggs Aug 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c9e900cd-4c6b-4027-b6ca-b93b55c3c5e7`.
