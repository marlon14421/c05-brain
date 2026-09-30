---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0126"
target_object: "T1106"
stix_relationship_id: "relationship--7eaf474f-7755-41d7-96c6-811889457be2"
---
# Relationship 9291: S0126 — uses → T1106

**Source object:** [[01 ATT&CK/S0126 - ComRAT|S0126: ComRAT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ComRAT](https://attack.mitre.org/software/S0126) can load a PE file from memory or the file system and execute it with CreateProcessW .(Citation: ESET ComRAT May 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--7eaf474f-7755-41d7-96c6-811889457be2`.
