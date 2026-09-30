---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0040"
target_object: "T1555.003"
stix_relationship_id: "relationship--1df7df54-c4c1-49f0-a0c3-11102db44f2c"
---
# Relationship 8448: G0040 — uses → T1555.003

**Source object:** [[01 ATT&CK/G0040 - Patchwork|G0040: Patchwork]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1555.003 - Credentials from Web Browsers|T1555.003: Credentials from Web Browsers]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Patchwork](https://attack.mitre.org/groups/G0040) dumped the login data database from \AppData\Local\Google\Chrome\User Data\Default\Login Data .(Citation: Cymmetria Patchwork)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1df7df54-c4c1-49f0-a0c3-11102db44f2c`.
