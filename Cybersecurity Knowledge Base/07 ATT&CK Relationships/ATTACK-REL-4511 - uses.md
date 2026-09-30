---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S9027"
target_object: "T1027"
stix_relationship_id: "relationship--c5afcc91-bdd7-489a-a9d5-9840f5ba2259"
---
# Relationship 4511: S9027 — uses → T1027

**Source object:** [[01 ATT&CK/S9027 - ANELLDR|S9027: ANELLDR]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[ANELLDR](https://attack.mitre.org/software/S9027) code implements anti-analysis techniques including control flow flattening and Mixed Boolean Arithmetic (MBA).(Citation: Trend Micro Earth Kasha Anel NOV 2024)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--c5afcc91-bdd7-489a-a9d5-9840f5ba2259`.
