---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0471"
target_object: "T1027.003"
stix_relationship_id: "relationship--5342c0fb-0f4d-456a-a7e7-525c60b7f82e"
---
# Relationship 8231: S0471 — uses → T1027.003

**Source object:** [[01 ATT&CK/S0471 - build_downer|S0471: build_downer]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.003 - Steganography|T1027.003: Steganography]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[build_downer](https://attack.mitre.org/software/S0471) can extract malware from a downloaded JPEG.(Citation: Trend Micro Tick November 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5342c0fb-0f4d-456a-a7e7-525c60b7f82e`.
