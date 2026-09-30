---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0090"
target_object: "T1027.015"
stix_relationship_id: "relationship--d88f8b58-2adb-4e8a-9adb-e51cbf88d4ab"
---
# Relationship 8048: G0090 — uses → T1027.015

**Source object:** [[01 ATT&CK/G0090 - WIRTE|G0090: WIRTE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[WIRTE](https://attack.mitre.org/groups/G0090) has compressed malicious files within RAR and ZIP archives for obfuscation. (Citation: Check Point Wirte NOV 2024)(Citation: Palo Alto Ashen Lepus DEC 2025)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--d88f8b58-2adb-4e8a-9adb-e51cbf88d4ab`.
