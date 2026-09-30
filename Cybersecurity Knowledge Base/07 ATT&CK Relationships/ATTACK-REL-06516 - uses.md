---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0134"
target_object: "T1189"
stix_relationship_id: "relationship--02fa0350-978f-4b61-b004-82380e70beee"
---
# Relationship 6516: G0134 — uses → T1189

**Source object:** [[01 ATT&CK/G0134 - Transparent Tribe|G0134: Transparent Tribe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1189 - Drive-by Compromise|T1189: Drive-by Compromise]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Transparent Tribe](https://attack.mitre.org/groups/G0134) has used websites with malicious hyperlinks and iframes to infect targeted victims with [Crimson](https://attack.mitre.org/software/S0115), [njRAT](https://attack.mitre.org/software/S0385), and other malicious tools.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Unit 42 ProjectM March 2016)(Citation: Talos Transparent Tribe May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--02fa0350-978f-4b61-b004-82380e70beee`.
