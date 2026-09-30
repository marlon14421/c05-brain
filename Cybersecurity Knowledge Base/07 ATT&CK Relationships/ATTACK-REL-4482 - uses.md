---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0625"
target_object: "T1027"
stix_relationship_id: "relationship--662f14ec-90c6-48f7-98c6-ba028ca38621"
---
# Relationship 4482: S0625 — uses → T1027

**Source object:** [[01 ATT&CK/S0625 - Cuba|S0625: Cuba]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[Cuba](https://attack.mitre.org/software/S0625) has used multiple layers of obfuscation to avoid analysis, including its Base64 encoded payload.(Citation: McAfee Cuba April 2021)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--662f14ec-90c6-48f7-98c6-ba028ca38621`.
