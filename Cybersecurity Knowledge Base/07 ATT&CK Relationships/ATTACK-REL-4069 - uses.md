---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1245"
target_object: "T1219"
stix_relationship_id: "relationship--aeeb9a14-a1e8-4721-8e07-2f25a21f7fa6"
---
# Relationship 4069: S1245 — uses → T1219

**Source object:** [[01 ATT&CK/S1245 - InvisibleFerret|S1245: InvisibleFerret]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1219 - Remote Access Tools|T1219: Remote Access Tools]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[InvisibleFerret](https://attack.mitre.org/software/S1245) has utilized remote access software including AnyDesk client through the “adc” module.(Citation: Esentire ContagiousInterview BeaverTail InvisibleFerret November 2024)(Citation: ESET Contagious Interview BeaverTail InvisibleFerret February 2025)(Citation: PaloAlto ContagiousInterview BeaverTail InvisibleFerret November 2023) [InvisibleFerret](https://attack.mitre.org/software/S1245) has also downloaded the AnyDesk client should it not already exist on the compromised host by searching for `C:/Program Files(x86)/AnyDesk/AnyDesk.exe`.(Citation: Zscaler ContagiousInterview BeaverTail InvisibleFerret November 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--aeeb9a14-a1e8-4721-8e07-2f25a21f7fa6`.
