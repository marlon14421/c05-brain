---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S1111"
target_object: "T1010"
stix_relationship_id: "relationship--36a93ca6-ad3b-468a-b5a3-d4676410ae1b"
---
# Relationship 4900: S1111 — uses → T1010

**Source object:** [[01 ATT&CK/S1111 - DarkGate|S1111: DarkGate]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1010 - Application Window Discovery|T1010: Application Window Discovery]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[DarkGate](https://attack.mitre.org/software/S1111) will search for cryptocurrency wallets by examining application window names for specific strings.(Citation: Ensilo Darkgate 2018) [DarkGate](https://attack.mitre.org/software/S1111) extracts information collected via NirSoft tools from the hosting process's memory by first identifying the window through the FindWindow API function.(Citation: Ensilo Darkgate 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--36a93ca6-ad3b-468a-b5a3-d4676410ae1b`.
