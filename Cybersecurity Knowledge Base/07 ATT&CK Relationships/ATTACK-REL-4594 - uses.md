---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0579"
target_object: "T1012"
stix_relationship_id: "relationship--93741cce-12ce-4cc0-9fa6-5db7d8a1309a"
---
# Relationship 4594: S0579 — uses → T1012

**Source object:** [[01 ATT&CK/S0579 - Waterbear|S0579: Waterbear]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1012 - Query Registry|T1012: Query Registry]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Waterbear](https://attack.mitre.org/software/S0579) can query the Registry key "HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\MSDTC\MTxOCI" to see if the value `OracleOcilib` exists.(Citation: Trend Micro Waterbear December 2019)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--93741cce-12ce-4cc0-9fa6-5db7d8a1309a`.
