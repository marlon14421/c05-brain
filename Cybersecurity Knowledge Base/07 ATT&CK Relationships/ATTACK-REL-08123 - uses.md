---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0138"
target_object: "T1189"
stix_relationship_id: "relationship--4fd205f2-656f-4211-b60b-510d53dfa8d3"
---
# Relationship 8123: G0138 — uses → T1189

**Source object:** [[01 ATT&CK/G0138 - Andariel|G0138: Andariel]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Andariel](https://attack.mitre.org/groups/G0138) has used watering hole attacks, often with zero-day exploits, to gain initial access to victims within a specific IP range.(Citation: AhnLab Andariel Subgroup of Lazarus June 2018)(Citation: TrendMicro New Andariel Tactics July 2018)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4fd205f2-656f-4211-b60b-510d53dfa8d3`.
