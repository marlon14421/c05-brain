---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1040"
target_object: "T1027.010"
stix_relationship_id: "relationship--5112b872-0d2e-48a7-ac5c-512a3720d46d"
---
# Relationship 9258: G1040 — uses → T1027.010

**Source object:** [[01 ATT&CK/G1040 - Play|G1040: Play]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Play](https://attack.mitre.org/groups/G1040) has used Base64-encoded PowerShell scripts for post exploit activities on compromised hosts.(Citation: Trend Micro Ransomware Spotlight Play July 2023)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5112b872-0d2e-48a7-ac5c-512a3720d46d`.
