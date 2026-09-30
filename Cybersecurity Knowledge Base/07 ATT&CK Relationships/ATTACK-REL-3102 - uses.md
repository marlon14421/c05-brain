---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0203"
target_object: "T1027"
stix_relationship_id: "relationship--5ef1c7d8-70bc-4634-b705-644f4d1db3b0"
---
# Relationship 3102: S0203 — uses → T1027

**Source object:** [[01 ATT&CK/S0203 - Hydraq|S0203: Hydraq]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Hydraq](https://attack.mitre.org/software/S0203) uses basic obfuscation in the form of spaghetti code.(Citation: Symantec Elderwood Sept 2012)(Citation: Symantec Trojan.Hydraq Jan 2010)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--5ef1c7d8-70bc-4634-b705-644f4d1db3b0`.
