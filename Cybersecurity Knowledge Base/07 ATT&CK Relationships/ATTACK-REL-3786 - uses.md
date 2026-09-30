---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0274"
target_object: "T1074.001"
stix_relationship_id: "relationship--dbdf85ca-504d-40f9-9023-ce8acdf99781"
---
# Relationship 3786: S0274 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0274 - Calisto|S0274: Calisto]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Calisto](https://attack.mitre.org/software/S0274) uses a hidden directory named .calisto to store data from the victim’s machine before exfiltration.(Citation: Securelist Calisto July 2018)(Citation: Symantec Calisto July 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--dbdf85ca-504d-40f9-9023-ce8acdf99781`.
