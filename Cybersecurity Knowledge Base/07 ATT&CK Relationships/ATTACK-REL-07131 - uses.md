---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1015"
target_object: "T1588.001"
stix_relationship_id: "relationship--f93c2e91-ab53-454b-a54d-085a5a3c5e80"
---
# Relationship 7131: G1015 — uses → T1588.001

**Source object:** [[01 ATT&CK/G1015 - Scattered Spider|G1015: Scattered Spider]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1588.001 - Malware|T1588.001: Malware]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Scattered Spider](https://attack.mitre.org/groups/G1015) has obtained malware to use at multiple stages of operations including information stealers, remote access tools, and ransomware.(Citation: Mandiant UNC3944 May 2025)(Citation: Check Point Scattered Spider JUL 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f93c2e91-ab53-454b-a54d-085a5a3c5e80`.
