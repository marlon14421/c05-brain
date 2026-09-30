---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0134"
target_object: "T1608.004"
stix_relationship_id: "relationship--087c222c-4108-4fbf-ac8f-983cd71548fa"
---
# Relationship 9223: G0134 — uses → T1608.004

**Source object:** [[01 ATT&CK/G0134 - Transparent Tribe|G0134: Transparent Tribe]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1608.004 - Drive-by Target|T1608.004: Drive-by Target]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[Transparent Tribe](https://attack.mitre.org/groups/G0134) has set up websites with malicious hyperlinks and iframes to infect targeted victims with [Crimson](https://attack.mitre.org/software/S0115), [njRAT](https://attack.mitre.org/software/S0385), and other malicious tools.(Citation: Proofpoint Operation Transparent Tribe March 2016)(Citation: Unit 42 ProjectM March 2016)(Citation: Talos Transparent Tribe May 2021)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--087c222c-4108-4fbf-ac8f-983cd71548fa`.
