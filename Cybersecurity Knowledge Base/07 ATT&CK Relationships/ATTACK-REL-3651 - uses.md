---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0264"
target_object: "T1027"
stix_relationship_id: "relationship--ec9e1757-50c1-4fd8-a0be-2694b1bc9e99"
---
# Relationship 3651: S0264 — uses → T1027

**Source object:** [[01 ATT&CK/S0264 - OopsIE|S0264: OopsIE]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1027 - Obfuscated Files or Information|T1027: Obfuscated Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[OopsIE](https://attack.mitre.org/software/S0264) uses the Confuser protector to obfuscate an embedded .Net Framework assembly used for C2. [OopsIE](https://attack.mitre.org/software/S0264) also encodes collected data in hexadecimal format before writing to files on disk and obfuscates strings.(Citation: Unit 42 OopsIE! Feb 2018)(Citation: Unit 42 OilRig Sept 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--ec9e1757-50c1-4fd8-a0be-2694b1bc9e99`.
