---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0257"
target_object: "T1140"
stix_relationship_id: "relationship--54c703f9-67ef-4622-afed-0ebbd2563e9e"
---
# Relationship 4822: S0257 — uses → T1140

**Source object:** [[01 ATT&CK/S0257 - VERMIN|S0257: VERMIN]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1140 - Deobfuscate-Decode Files or Information|T1140: Deobfuscate/Decode Files or Information]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[VERMIN](https://attack.mitre.org/software/S0257) decrypts code, strings, and commands to use once it's on the victim's machine.(Citation: Unit 42 VERMIN Jan 2018)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--54c703f9-67ef-4622-afed-0ebbd2563e9e`.
