---
type: "ATT&CK Relationship"
source: "MITRE ATT&CK Enterprise STIX"
relationship: "uses"
source_object: "S0396"
target_object: "T1106"
stix_relationship_id: "relationship--00ba134e-1833-4dde-bf4e-7ec45271e8a6"
---
# Relationship 4843: S0396 — uses → T1106

**Source object:** [[01 ATT&CK/S0396 - EvilBunny|S0396: EvilBunny]]  
**Relationship:** `uses`  
**Target object:** [[01 ATT&CK/T1106 - Native API|T1106: Native API]]

## Meaning for defensive analysis

Connects a behavior, group, campaign, or software object to something it uses. This is a catalog relationship, not proof of current activity.

## Source description

[EvilBunny](https://attack.mitre.org/software/S0396) has used various API calls as part of its checks to see if the malware is running in a sandbox.(Citation: Cyphort EvilBunny Dec 2014)

## How an AI should use this fact

Retrieve this edge together with both linked records. Preserve its direction and relationship label, cite the source object identifiers, and avoid upgrading a catalog association into an incident claim. For operational recommendations, inspect the linked records and corroborate against current telemetry and authoritative product guidance.

## Provenance

[MITRE ATT&CK STIX Enterprise dataset](https://github.com/mitre/cti/tree/master/enterprise-attack), snapshot downloaded 2026-09-30. STIX relationship ID: `relationship--00ba134e-1833-4dde-bf4e-7ec45271e8a6`.
