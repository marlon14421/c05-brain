---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1246"
target_object: "T1041"
stix_relationship_id: "relationship--13953007-34e2-44e9-96af-53bed8f4413c"
---
# Relationship 3128: S1246 — uses → T1041

**Source object:** [[01 ATT&CK/S1246 - BeaverTail|S1246: BeaverTail]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1041 - Exfiltration Over C2 Channel|T1041: Exfiltration Over C2 Channel]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[BeaverTail](https://attack.mitre.org/software/S1246) has exfiltrated data collected from victim devices to C2 servers.(Citation: Socket BeaverTail XORIndex HexEval Contagious Interview July 2025)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023)(Citation: PaloAlto Unit42 ContagiousInterview BeaverTail InvisibileFerret October 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--13953007-34e2-44e9-96af-53bed8f4413c`.
