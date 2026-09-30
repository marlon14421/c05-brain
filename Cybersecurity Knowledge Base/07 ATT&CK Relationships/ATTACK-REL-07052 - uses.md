---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0634"
target_object: "T1036"
stix_relationship_id: "relationship--f09c9f4a-345f-4352-aaba-7b0b0a24085c"
---
# Relationship 7052: S0634 — uses → T1036

**Source object:** [[01 ATT&CK/S0634 - EnvyScout|S0634: EnvyScout]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1036 - Masquerading|T1036: Masquerading]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[EnvyScout](https://attack.mitre.org/software/S0634) has used folder icons for malicious files to lure victims into opening them.(Citation: MSTIC Nobelium Toolset May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f09c9f4a-345f-4352-aaba-7b0b0a24085c`.
