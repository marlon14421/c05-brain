---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0266"
target_object: "T1210"
stix_relationship_id: "relationship--e56f602c-ec9f-46f0-a52f-45b90220314e"
---
# Relationship 2999: S0266 — uses → T1210

**Source object:** [[01 ATT&CK/S0266 - TrickBot|S0266: TrickBot]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1210 - Exploitation of Remote Services|T1210: Exploitation of Remote Services]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[TrickBot](https://attack.mitre.org/software/S0266) utilizes EternalBlue and EternalRomance exploits for lateral movement in the modules wormwinDll, wormDll, mwormDll, nwormDll, tabDll.(Citation: ESET Trickbot Oct 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--e56f602c-ec9f-46f0-a52f-45b90220314e`.
