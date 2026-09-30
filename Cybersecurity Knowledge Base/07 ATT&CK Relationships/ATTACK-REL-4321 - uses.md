---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0458"
target_object: "T1074.001"
stix_relationship_id: "relationship--4b03f718-f89a-4652-b3be-5cbe4e0e044f"
---
# Relationship 4321: S0458 — uses → T1074.001

**Source object:** [[01 ATT&CK/S0458 - Ramsay|S0458: Ramsay]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1074.001 - Local Data Staging|T1074.001: Local Data Staging]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Ramsay](https://attack.mitre.org/software/S0458) can stage data prior to exfiltration in %APPDATA%\Microsoft\UserSetting and %APPDATA%\Microsoft\UserSetting\MediaCache .(Citation: Eset Ramsay May 2020)(Citation: Antiy CERT Ramsay April 2020)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--4b03f718-f89a-4652-b3be-5cbe4e0e044f`.
