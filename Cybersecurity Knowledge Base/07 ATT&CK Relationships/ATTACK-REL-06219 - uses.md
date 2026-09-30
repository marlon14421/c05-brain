---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1051"
target_object: "T1027.010"
stix_relationship_id: "relationship--203e846e-c99d-457f-80b7-11cba574a869"
---
# Relationship 6219: G1051 — uses → T1027.010

**Source object:** [[01 ATT&CK/G1051 - Medusa Group|G1051: Medusa Group]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.010 - Command Obfuscation|T1027.010: Command Obfuscation]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Medusa Group](https://attack.mitre.org/groups/G1051) has obfuscated PowerShell scripts with Base64 encoding.(Citation: CISA Medusa Group Medusa Ransomware March 2025) [Medusa Group](https://attack.mitre.org/groups/G1051) has also obfuscated the code of dropped kernel drivers using a software known as Safengine Shielden which randomized the code through code mutations and then leveraged an embedded virtual machine interpreter to execute the code.(Citation: Palo Alto Unit 42 Medusa Group Medusa Ransomware January 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--203e846e-c99d-457f-80b7-11cba574a869`.
