---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0027"
target_object: "T1027.015"
stix_relationship_id: "relationship--3d63e19a-2b2b-4b00-834e-c7d6d5d1f8bb"
---
# Relationship 5499: G0027 — uses → T1027.015

**Source object:** [[01 ATT&CK/G0027 - Threat Group-3390|G0027: Threat Group-3390]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027.015 - Compression|T1027.015: Compression]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Threat Group-3390](https://attack.mitre.org/groups/G0027) malware is compressed with LZNT1 compression.(Citation: Nccgroup Emissary Panda May 2018)(Citation: Securelist LuckyMouse June 2018)(Citation: Unit42 Emissary Panda May 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--3d63e19a-2b2b-4b00-834e-c7d6d5d1f8bb`.
