---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0138"
target_object: "T1027"
stix_relationship_id: "relationship--8e82a523-fc73-4f3b-98dc-3b1e7199cd93"
---
# Relationship 4456: S0138 — uses → T1027

**Source object:** [[01 ATT&CK/S0138 - OLDBAIT|S0138: OLDBAIT]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OLDBAIT](https://attack.mitre.org/software/S0138) obfuscates internal strings and unpacks them at startup.(Citation: FireEye APT28)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--8e82a523-fc73-4f3b-98dc-3b1e7199cd93`.
