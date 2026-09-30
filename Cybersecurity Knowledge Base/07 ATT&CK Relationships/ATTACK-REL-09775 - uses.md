---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1096"
target_object: "T1673"
stix_relationship_id: "relationship--f2bc5108-3783-4f46-a0dd-60abe1a55987"
---
# Relationship 9775: S1096 — uses → T1673

**Source object:** [[01 ATT&CK/S1096 - Cheerscrypt|S1096: Cheerscrypt]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1673 - Virtual Machine Discovery|T1673: Virtual Machine Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

Cheerscrypt has leveraged `esxcli vm process list` in order to gather a list of running virtual machines to terminate them.(Citation: Trend Micro Cheerscrypt May 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--f2bc5108-3783-4f46-a0dd-60abe1a55987`.
