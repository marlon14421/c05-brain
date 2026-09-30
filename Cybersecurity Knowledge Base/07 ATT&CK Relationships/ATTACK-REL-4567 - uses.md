---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0469"
target_object: "T1071.001"
stix_relationship_id: "relationship--51151669-a076-4d4a-af68-cf303baf01d5"
---
# Relationship 4567: S0469 — uses → T1071.001

**Source object:** [[01 ATT&CK/S0469 - ABK|S0469: ABK]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1071.001 - Web Protocols|T1071.001: Web Protocols]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ABK](https://attack.mitre.org/software/S0469) has the ability to use HTTP in communications with C2.(Citation: Trend Micro Tick November 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--51151669-a076-4d4a-af68-cf303baf01d5`.
