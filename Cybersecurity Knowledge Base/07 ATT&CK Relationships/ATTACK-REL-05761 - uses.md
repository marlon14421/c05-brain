---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9021"
target_object: "T1055"
stix_relationship_id: "relationship--dc78facd-a71c-45d8-bf93-67effda51dfa"
---
# Relationship 5761: S9021 — uses → T1055

**Source object:** [[01 ATT&CK/S9021 - DOWNIISSA|S9021: DOWNIISSA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1055 - Process Injection|T1055: Process Injection]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DOWNIISSA](https://attack.mitre.org/software/S9021) can inject shellcode directly into process memory including WINWORD.exe and msiexec.exe.(Citation: Kaspersky LODEINFO OCT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dc78facd-a71c-45d8-bf93-67effda51dfa`.
