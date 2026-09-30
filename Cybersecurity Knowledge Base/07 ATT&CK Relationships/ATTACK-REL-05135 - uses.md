---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0005"
target_object: "T1027.003"
stix_relationship_id: "relationship--1aad8f36-aec7-4210-8edb-7ad3dd14f5ed"
---
# Relationship 5135: C0005 — uses → T1027.003

**Source object:** [[01 ATT&CK/C0005 - Operation Spalax|C0005: Operation Spalax]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

For [Operation Spalax](https://attack.mitre.org/campaigns/C0005), the threat actors used packers that read pixel data from images contained in PE files' resource sections and build the next layer of execution from the data.(Citation: ESET Operation Spalax Jan 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1aad8f36-aec7-4210-8edb-7ad3dd14f5ed`.
