---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0128"
target_object: "T1124"
stix_relationship_id: "relationship--576c98f3-5753-4242-a5e3-7c0f769c27a1"
---
# Relationship 9985: G0128 — uses → T1124

**Source object:** [[01 ATT&CK/G0128 - ZIRCONIUM|G0128: ZIRCONIUM]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1124 - System Time Discovery|T1124: System Time Discovery]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[ZIRCONIUM](https://attack.mitre.org/groups/G0128) has used a tool to capture the time on a compromised host in order to register it with C2.(Citation: Zscaler APT31 Covid-19 October 2020)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--576c98f3-5753-4242-a5e3-7c0f769c27a1`.
