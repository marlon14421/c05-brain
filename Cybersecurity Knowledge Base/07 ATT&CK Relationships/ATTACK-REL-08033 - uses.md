---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9021"
target_object: "T1218.007"
stix_relationship_id: "relationship--70dd01ce-66e3-48e0-856a-1ed93e4d851a"
---
# Relationship 8033: S9021 — uses → T1218.007

**Source object:** [[01 ATT&CK/S9021 - DOWNIISSA|S9021: DOWNIISSA]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1218.007 - Msiexec|T1218.007: Msiexec]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[DOWNIISSA](https://attack.mitre.org/software/S9021) can create an instance of msiexec.exe and inject [LODEINFO](https://attack.mitre.org/software/S9020) shellcode into the memory of the process.(Citation: Kaspersky LODEINFO OCT 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--70dd01ce-66e3-48e0-856a-1ed93e4d851a`.
