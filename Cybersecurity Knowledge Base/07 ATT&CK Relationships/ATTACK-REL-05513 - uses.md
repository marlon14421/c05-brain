---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0143"
target_object: "T1543.003"
stix_relationship_id: "relationship--1fbee829-fe84-4a48-a943-5be81abfb43c"
---
# Relationship 5513: G0143 — uses → T1543.003

**Source object:** [[01 ATT&CK/G0143 - Aquatic Panda|G0143: Aquatic Panda]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1543.003 - Windows Service|T1543.003: Windows Service]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Aquatic Panda](https://attack.mitre.org/groups/G0143) created new Windows services for persistence that masqueraded as legitimate Windows services via name change.(Citation: Crowdstrike HuntReport 2022)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--1fbee829-fe84-4a48-a943-5be81abfb43c`.
