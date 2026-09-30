---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "G1052"
target_object: "T1589"
stix_relationship_id: "relationship--9dd32755-a5a0-4108-a396-8ac9514497a8"
---
# Relationship 3113: G1052 — uses → T1589

**Source object:** [[01 ATT&CK/G1052 - Contagious Interview|G1052: Contagious Interview]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1589 - Gather Victim Identity Information|T1589: Gather Victim Identity Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Contagious Interview](https://attack.mitre.org/groups/G1052) has researched specific professional groups such as software developers for targeting.(Citation: Socket HexEval BeaverTail Contagious Interview June 2025)(Citation: SecurityScorecard Contagious Interview October 2024)(Citation: Securonix Contagious Interview DEVPOPPER April 2024)(Citation: SecurityScorecard Contagious Interview FamousChollima October 2024)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)(Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024) [Contagious Interview](https://attack.mitre.org/groups/G1052) has also researched individuals who work in roles related to cryptocurrency and blockchain technologies.(Citation: Sentinel One Contagious Interview ClickFix September 2025)(Citation: Sekoia ClickFake 2025)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--9dd32755-a5a0-4108-a396-8ac9514497a8`.
