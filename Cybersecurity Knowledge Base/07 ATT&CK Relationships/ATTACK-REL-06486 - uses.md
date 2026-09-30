---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1024"
target_object: "T1027.001"
stix_relationship_id: "relationship--d50f6966-5085-48e3-bf48-e6e252a0b6be"
---
# Relationship 6486: G1024 — uses → T1027.001

**Source object:** [[01 ATT&CK/G1024 - Akira|G1024: Akira]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.001 - Binary Padding|T1027.001: Binary Padding]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Akira](https://attack.mitre.org/groups/G1024) has used binary padding to obfuscate payloads.(Citation: Cisco Akira Ransomware OCT 2024)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d50f6966-5085-48e3-bf48-e6e252a0b6be`.
