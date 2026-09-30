---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "C0032"
target_object: "T1074.001"
stix_relationship_id: "relationship--2545e3a8-751e-443b-ad4e-da1843014f6b"
---
# Relationship 6319: C0032 — uses → T1074.001

**Source object:** [[01 ATT&CK/C0032 - C0032|C0032: C0032]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

During the [C0032](https://attack.mitre.org/campaigns/C0032) campaign, [TEMP.Veles](https://attack.mitre.org/groups/G0088) used staging folders that are infrequently used by legitimate users or processes to store data for exfiltration and tool deployment.(Citation: FireEye TRITON 2019)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--2545e3a8-751e-443b-ad4e-da1843014f6b`.
