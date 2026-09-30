---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G0049"
target_object: "T1204.002"
stix_relationship_id: "relationship--557d3feb-0699-429e-bc83-ff114cf138ef"
---
# Relationship 5846: G0049 — uses → T1204.002

**Source object:** [[01 ATT&CK/G0049 - OilRig|G0049: OilRig]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1204.002 - Malicious File|T1204.002: Malicious File]]

## Defensive meaning

Records a catalog association between the source object and something it uses. This is not evidence that the behavior is active in a particular environment.

## Source description

[OilRig](https://attack.mitre.org/groups/G0049) has delivered macro-enabled documents that required targets to click the "enable content" button to execute the payload on the system.(Citation: Unit 42 OopsIE! Feb 2018)(Citation: Unit 42 QUADAGENT July 2018)(Citation: Crowdstrike Helix Kitten Nov 2018)(Citation: Check Point APT34 April 2021)(Citation: ClearSky OilRig Jan 2017)

## AI use

Retrieve this edge with both endpoint records. Preserve direction and type, cite the identifiers, and distinguish catalog information from observed events. Verify recommendations against current environment evidence and authoritative product guidance.

## Provenance

[MITRE ATT&CK Enterprise STIX](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--557d3feb-0699-429e-bc83-ff114cf138ef`.
